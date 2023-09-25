pipeline {
  agent any
  stages {
    stage('version') {
      steps {
         bat 'cd %nohup%'
         sh 'python --version'
      }
    }
    stage('hello') {
      steps {
         bat 'cd %nohup%'
         sh 'python hello.py'
      }
    }
  }
}
