pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        echo 'version step'
        bat 'python --version'
      }
    }
    stage('hello') {
      steps {
        echo 'executing step'
        bat 'python my_test.py'
      }
    }
  }
}
