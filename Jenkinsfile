pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat '''cd %python%
        python --version'''
      }
    }
    stage('hello') {
      steps {
       bat '''cd %python%
       python hello.py'''
      }
    }
  }
}
