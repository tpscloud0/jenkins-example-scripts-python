pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        script{
            bat 'python --verison'
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

