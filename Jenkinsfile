pipeline {
  agent {
    docker {
      image 'edge-jenkins:latest'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh 'which jps'
      }
    }
  }
}