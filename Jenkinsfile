pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        script{
              bat 'python -v'
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
