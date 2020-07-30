pipeline {
  agent {
    node {
      label 'test'
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