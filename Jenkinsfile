pipeline {
  agent {
    docker {
      image 'docker'
    }
    
  }
  stages {
    stage('DIT') {
      steps {
        echo 'This is DIT env'
      }
    }
  }
  environment {
    DEV = ''
  }
}