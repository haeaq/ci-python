pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'hello world'
      }
    }
    stage('Run') {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
