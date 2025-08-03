pipeline {
  agent {
    node {
      label 'node01'
    }

  }
  stages {
    stage('dev') {
      steps {
        sh 'go test ./...'
      }
    }

  }
}