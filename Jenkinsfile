pipeline {
  agent {
    docker {
      image 'edge-jenkins:latest'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh '''which jps
ls -l /usr/bin/ | grep jps'''
      }
    }
  }
}