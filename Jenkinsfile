pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        sh 'echo "hello "world"'
      }
    }

    stage('memory') {
      steps {
        sh 'free -m'
      }
    }

  }
}