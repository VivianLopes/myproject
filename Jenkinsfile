pipeline {
  agent {
    docker {
      image 'node 6.3'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh ' dmesg | grep Linux | grep version'
      }
    }
  }
}