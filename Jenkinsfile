pipeline {
   agent any

   tools {
      maven "MAVEN_HOME"
   }

   stages {
      stage('Compile') {
         steps {
            sh "mvn clean compile"
         }
         }
      stage('Test') {
          steps {
            sh "mvn clean test"
            
          }

      }
      stage("Deploy") {
          steps {
            sh "mvn clean install"
            
          }

          }


      }

      }

