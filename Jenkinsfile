pipeline {
  agent {
    docker {
      args '-p 3000:3000'
      image 'node:6-alpine'
    }
    
  }
  stages {
    stage('Buld') {
      steps {
        echo 'Hello'
        sh 'npm init'
      }
    }
  }
}