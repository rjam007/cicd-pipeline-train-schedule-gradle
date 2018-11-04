pipeline {
  agent any
    stages {
       stage ('build') {
         steps {
           echo "hello im building"
          }
       }
    }
    post {
      always {
         echo "i will say hello always"
      }
   } 
}
