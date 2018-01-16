pipeline {
  agent {
    docker {
      image 'node:6-alpain'
      args '-p 3000:3000'
    }
    
  }
  stages {
    stage('Buld') {
      steps {
        echo 'Hello'
        sh 'npm install'
      }
    }
  }
}