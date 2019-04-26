pipeline {
  agent any
  stages {
    stage('docker image') {
      steps {
        sh '''







  docker build -t demo .

'''
      }
    }
    stage('Run docker') {
      steps {
        sh '''#docker stop demo 



















#docker rm demo docker run -t -p 3000:3000 demo'''
      }
    }
  }
}