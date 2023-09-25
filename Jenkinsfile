pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat '''cd %path%
        call python --version'''
      }
    }
    stage('hello') {
      steps {
       bat '''cd %path%
       call python hello.py'''
      }
    }
  }
}
