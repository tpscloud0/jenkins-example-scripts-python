pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        script{
              bat 'cd C:\Program Files\Python310'
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
