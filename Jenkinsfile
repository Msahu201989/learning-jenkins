pipeline {
   agent any

    stages {
        stage('Foo') {
            steps {
              echo 'Hello world'
            }
        }

        stage('Bar') {
                steps {
                  echo 'Hello world'
                }
            }
    }

    post {
       always {
           echo 'I will always say Hello again!'
       }
        }
    }
