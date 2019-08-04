node {
   
   stage('Code checkout') { // for display purposes
    git 'https://github.com/itrainjaquar/maven_apps.git'  
   }
   stage('Build') {
     withMaven(jdk: 'JDK-1.8', maven: 'Maven-3.6.1') {
      sh 'mvn clean compile'
     }
   }
   stage('Unit test') {
     withMaven(jdk: 'JDK-1.8', maven: 'Maven-3.6.1') {
      sh 'mvn test'
     }
   }
   stage('Package') {
     withMaven(jdk: 'JDK-1.8', maven: 'Maven-3.6.1') {
      sh 'mvn package'
     }
   }
   stage('Deploy to Dev') {
    
   }
   stage('Deploy to Test') {
    
   }
   stage('Deploy to Stage') {
    
   }
   stage('Deploy to Prod') {
    
   }
   
}
