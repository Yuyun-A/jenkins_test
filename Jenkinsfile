pipeline {
  agent {
    node {
      label 'nx'
    }

  }
  stages {
    stage('move') {
      agent {
        docker {
          image 'hello-world'
        }

      }
      steps {
        echo 'OK'
      }
    }

    stage('docker run') {
      agent any
      steps {
        echo 'or NOT?'
      }
    }

  }
}