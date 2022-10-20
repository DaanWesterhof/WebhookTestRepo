pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        echo 'version step'
        bat 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        echo 'executing step'
        bat 'python3 my_test.py'
      }
    }
  }
}
