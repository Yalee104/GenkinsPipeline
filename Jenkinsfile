pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'joyarzun/node-6-alpine-glib'
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