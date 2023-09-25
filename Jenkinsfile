pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat '''cd %python%
        call python --version'''
      }
    }
    stage('hello') {
      steps {
       bat '''cd %python%
       call python hello.py'''
      }
    }
  }
}
