pipeline {

  agent any

  stages {

    stage('Code Quality') {
      steps {
        echo 'Code Quality'
      }
    }

    stage('Style Checks') {
    when {
      branch 'master'
      }

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
    
    stage('Auto Trigger') {
      steps {
        echo 'Auto Trigger'
      }
    }
      stage('Learning Auto Trigger') {
      steps {
        echo 'Learning Auto Trigger'
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
