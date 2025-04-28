pipeline {
  agent any
  stages {
    stage('move') {
      agent {
        node {
          label 'nx'
        }

      }
      steps {
        sh '''cd ${ISAAC_ROS_WS}
cd src/isaac_ros_common/'''
      }
    }

    stage('docker run') {
      steps {
        sh './scripts/run_mydev.sh '
      }
    }

  }
}