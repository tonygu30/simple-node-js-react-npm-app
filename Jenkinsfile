pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:latest'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
  }
}