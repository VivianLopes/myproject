pipeline {
  agent any
  stages {
    stage('shell') {
      steps {
        sh ' dmesg | grep Linux | grep version'
      }
    }
  }
}