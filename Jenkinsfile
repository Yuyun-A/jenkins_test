pipeline {
  agent any
  stages {
    stage('build') {
      agent {
        node {
          label 'nx'
        }

      }
      steps {
        echo 'building...'
      }
    }

  }
}