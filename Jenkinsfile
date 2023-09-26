pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        script{
              bat 'cd'
        }
      }
    }
    stage('hello') {
      steps {
         script{
            bat 'python.exe hello.py'
         } 
      }
    }
  }
}
