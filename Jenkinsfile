pipeline {
  agent {
    docker {
      image 'maven:3.5.3'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh '''cat /proc/version || true
cat /etc/os-release'''
      }
    }
  }
}