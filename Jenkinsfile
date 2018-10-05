pipeline {
  agent {
    docker {
      image 'maven:3.5.3'
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