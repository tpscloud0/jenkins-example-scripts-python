pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        sh '''cd %nohup%
         python --version'''
      }
    }
    stage('hello') {
      steps {
        sh '''cd %path%
         python hello.py'''
      }
    }
  }
}
