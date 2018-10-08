pipeline {
  agent {
    docker {
      image 'edge-jenkins:latest'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh '''pwd
cat /etc/os-release
which make'''
      }
    }
  }
}