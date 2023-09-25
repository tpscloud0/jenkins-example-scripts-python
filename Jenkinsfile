pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'cd %python%'
        bat 'cd'
        bat 'python --version'
      }
    }
    stage('hello') {
      steps {
        bat 'cd %python%'
        bat 'cd'
        bat 'python hello.py'
      }
    }
  }
}
