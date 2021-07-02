pipeline {
   agent any
   stages {

        stage("Git checkout"){
          steps {
           git credentialsId: 'github-cred', url: 'https://github.com/demodevops2/java-hello-world-webapp.git'
    }
          
           stage("Maven build"){
              stpes {
               echo "build src code"
              }
           }
           
}




}

}
