pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            echo 'This is build'
            
          },
          "test": {
            echo 'This is test'
            
          }
        )
      }
    }
  }
}