pipeline {
   agent any
    stages {
      stage("Git checkout"){
        steps{
         git credentialsId: 'github-cred', url: 'https://github.com/demodevops2/java-hello-world-webapp.git'
        }

      }
      
      stage("java build stage"){
        steps{
          sh 'mvn clean package'  
        }

      }



    } 
}    
