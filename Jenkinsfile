pipeline {
  agent any
  stages {
    stage('prebuild') {
      steps {
        echo 'clone repo'
      }
    }

    stage('Build') {
      steps {
        echo 'Build inprogress'
      }
    }

    stage('Testing') {
      steps {
        echo 'Test completed'
      }
    }

    stage('approval') {
      steps {
        echo 'Approved'
      }
    }

    stage('Deployed') {
      steps {
        echo 'Successfully Deployed'
      }
    }

  }
}