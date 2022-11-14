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
}