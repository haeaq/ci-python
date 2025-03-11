pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'hello world'
        sh 'docker ps'
      }
    }
    stage('Run') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
