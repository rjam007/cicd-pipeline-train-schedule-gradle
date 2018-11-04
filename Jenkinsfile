pipeline {
  agent any
    stages {
       stage ('build') {
         steps {
           echo "hello im building"
           sh './gradlew build'
          }
       }
    }
    post {
      always {
         echo "i will say hello always"
      }
   } 
}
