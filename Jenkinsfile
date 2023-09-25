pipeline {
  agent any
  stages {
    stage('version') {
      steps {
         bat '''cd %path%
         python3 --version'''
      }
    }
    stage('hello') {
      steps {
         bat '''cd %path%
         python3 hello.py'''
      }
    }
  }
}
