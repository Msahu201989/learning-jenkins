pipeline {

  agent {
    node 'worskstation'
    }

  stages {

    stage('Code Quality') {
      steps {
        echo 'Code Quality'
      }
    }

    stage('Style Checks') {
//     when {
//       branch 'main'
//       }

      steps {
        echo 'Code Quality'
      }
    }

    stage('Unit Tests') {
      steps {
        echo 'Unit tests'
      }
    }

    stage('Download Dependencies') {
         steps {
        echo 'Download Dependencies'
      }
    }

    stage('Prepare Artifact') {
      steps {
        echo 'Prepare Artifact'
      }
    }

    stage('Publish Artifact') {
      steps {
        echo 'Publish Artifact'
      }
    }

    post {
       always {
           echo 'I will always say Hello again!'
       }
        }
    }
