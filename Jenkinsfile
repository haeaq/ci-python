pipeline {
  agent {
    docker { image 'bitnami/python:3.8.20-debian-12-r4'}
  }
  stages {
    stage('Run') {
      steps {
        echo 'hello world'
        sh 'python3 hello.py'
      }
    }
  }
}
