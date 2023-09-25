pipeline {
  agent any
  stages {
    stage('version') {
      steps {
         bat '''cd %python%
         python3 --version'''
      }
    }
    stage('hello') {
      steps {
         bat '''cd %python%
         python3 hello.py'''
      }
    }
  }
}
