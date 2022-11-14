pipeline {
   agent {
     node { label 'workstation'}
   }
    environment {
        NEWRELIC_API_KEY = credentials('ansible1')
    }
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