pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        script{
              bat 'python --version'
        }
      }
    }
    stage('hello') {
      steps {
         script{
            bat 'python hello.py'
         } 
      }
    }
  }
}
