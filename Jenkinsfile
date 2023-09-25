pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'cd %python%'
        bat 'python --version'
      }
    }
    stage('hello') {
      steps {
        bat 'cd %python%'
        bat 'python hello.py'
      }
    }
  }
}
