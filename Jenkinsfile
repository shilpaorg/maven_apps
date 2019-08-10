node {
   
   stage('Code Checkout') {
     git credentialsId: 'githubID', url: 'https://github.com/itrainjaquar/maven_apps.git' 
   }
   stage('Compile') {
      sh 'mvn clean compile'
   }
   stage('Unit Test') {
     sh 'mvn test' 
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
   stage('Deploy to Prod') {
      
   }
}
