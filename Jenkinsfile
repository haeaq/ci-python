pipeline {
  agent {
    docker { image 'python:3.9.20-alpine3.20'}
  }
  stages {
    stage('Run') {
      steps {
        sh 'python3 hello.py'
      }
    }

  }
}
