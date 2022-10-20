pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        echo 'version step'
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        echo 'executing step'
        sh 'python3 my_test.py'
      }
    }
  }
}
