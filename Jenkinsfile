pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        script{
              def version_numbers = bat(script: 'python hello.py', returnStdout: true)
              def versions_as_array = version_numbers.split('\n')
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
def version_numbers = bat(script: 'python get_version_numbers.py', returnStdout: true)
                def versions_as_array = version_numbers.split('\n')
