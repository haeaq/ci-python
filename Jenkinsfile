pipeline {
  agent any
  stages {
    stage('check py version') {
      steps {
        sh 'python -version'
        echo 'version checked'
      }
    }

    stage('run') {
      steps {
        sh 'python hello.py'
      }
    }

  }
}