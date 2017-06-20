pipeline {
  agent any
  stages {
    stage('system testing') {
      steps {
        parallel(
          "system testing": {
            echo 'hello world'
            
          },
          "bug fix": {
            echo 'hello'
            
          }
        )
      }
    }
    stage('') {
      steps {
        parallel(
          "uat": {
            echo 'hello'
            
          },
          "end to end": {
            echo 'hello'
            
          }
        )
      }
    }
  }
}