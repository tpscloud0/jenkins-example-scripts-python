pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'cd %python%'
        bat 'pwd'
        bat 'python --version'
      }
    }
    stage('hello') {
      steps {
        bat 'cd %python%'
        bat 'pwd'
        bat 'python hello.py'
      }
    }
  }
}
