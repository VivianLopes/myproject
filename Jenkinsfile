pipeline {
  agent {
    docker {
      image 'edge-jenkins:latest'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh '''cat /etc/os-release
su -
apt-get install make'''
      }
    }
  }
}