pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        script{
              sh 'python --version'
        }
      }
    }
    stage('hello') {
      steps {
         script{
            sh 'python hello.py'
         } 
      }
    }
  }
}
