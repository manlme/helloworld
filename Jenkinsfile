pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        parallel(
          "build": {
            echo 'build'
            
          },
          "build2": {
            echo 'build2'
            
          },
          "build3": {
            echo 'build3'
            
          }
        )
      }
    }
    stage('test') {
      steps {
        echo 'test'
      }
    }
    stage('deploy') {
      steps {
        echo 'deploy'
      }
    }
  }
}