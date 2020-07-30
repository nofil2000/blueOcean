pipeline {
  agent none
  stages {
    stage('test1') {
      steps {
        echo '$test'
        sh 'echo "Hello"'
      }
    }

  }
  environment {
    test = 'x'
  }
}