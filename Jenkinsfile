pipeline {
  agent {
    docker {
      image 'nodejs'
    }

  }
  stages {
    stage('test1') {
      steps {
        echo '$test'
        sh 'echo hello'
      }
    }

  }
  environment {
    test = 'x'
  }
}