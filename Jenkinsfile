pipeline {
  agent any
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

    stage('print') {
      steps {
        echo 'Hello from BlueOcean'
      }
    }

  }
}