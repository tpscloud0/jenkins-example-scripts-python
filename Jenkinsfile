pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat '''cd %path%
        python --version'''
      }
    }
    stage('hello') {
      steps {
       bat '''cd %path%
       python hello.py'''
      }
    }
  }
}
