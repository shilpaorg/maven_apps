node {
   
   stage('Code Checkout') {
     git credentialsId: 'githubID', url: 'https://github.com/itrainjaquar/maven_apps.git' 
   }
   stage('Compile') {
      withMaven(jdk: 'JDK-1.8', maven: 'Maven-3.6.0') {
      sh 'mvn clean compile'
      }
      
    }
   stage('Unit Test') {
      withMaven(jdk: 'JDK-1.8', maven: 'Maven-3.6.0') {
       sh 'mvn test' 
     }
   }
   stage('Code analysis') {
      
   }
   stage('Archive') {
      
   }
   stage('Build Docker image') {
      
   }
   stage('Push Docker image') {
      
   }
   stage('Deploy to Dev') {
      
   }
   stage('Deploy to Prod of') {
      
   }
}
