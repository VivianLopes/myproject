pipeline {
  agent {
    docker {
      image 'maven:3.5.3'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh '''cat /etc/os-release
apt-get install make'''
      }
    }
  }
}