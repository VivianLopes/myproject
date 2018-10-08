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
mkdir foo
mkdir ../bar
ls -R ..
cat /etc/os-release
which make'''
      }
    }
  }
}