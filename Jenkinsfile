pipeline {
  agent agent1
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('hello') {
      steps {
        sh 'python3 my_test.py'
      }
    }
  }
}
