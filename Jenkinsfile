pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:6-alpine with glibc'
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