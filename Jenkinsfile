pipeline {
  agent {
    docker {
      image 'node:8-alpine'
      args '-p 3000:3000'
    }

  }
  stages {
    stage('docker image') {
      steps {
        sh 'docker build -t demo .'
      }
    }
  }
}