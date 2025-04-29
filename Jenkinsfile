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
        sh '''docker run hello-world
cd ${ISAAC_ROS_WS}
cd src/isaac_ros_common/'''
      }
    }

    stage('docker run') {
      agent {
        node {
          label 'nx'
        }

      }
      steps {
        sh './scripts/run_mydev.sh '
      }
    }

  }
}