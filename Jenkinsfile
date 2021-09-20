pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
  environment {
    image = 'node:6-alpine'
    Args = '-p 3000:3000'
  }
}