pipeline {
  agent {
    node {
      label 'nx'
    }

  }
  stages {
    stage('move') {
      agent {
        node {
          label 'nx'
        }

      }
      steps {
        echo 'OK'
      }
    }

    stage('docker run') {
      agent {
        node {
          label 'nx'
        }

      }
      steps {
        echo 'or NOT?'
      }
    }

  }
}