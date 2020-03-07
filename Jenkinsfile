pipeline {
   agent any

   stages {
      stage('Build & Test') {
         steps {
            git 'git@github.com:Natanael22/do25-alura-forum.git'

            sh "mvn clean test"
         }
      }
   }
}
