pipeline {

  agent any

  stages {

    stage('Code Quality') {
      steps {
        echo 'Code Quality'
      }
    }

    stage('Style Checks') {
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
      when { tag "1.0.1" }
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


  }

}
