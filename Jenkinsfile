pipeline {
  agent {
    docker {
      image 'node 6.3'
    }

  }
  stages {
    stage('shell') {
      steps {
        sh '''echo "This experiment started"
cat /proc/1/cgroup
whoami || true
hostname || true
which make  || true
make -h  || true
'''
      }
    }
  }
}