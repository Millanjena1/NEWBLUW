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

    stage('as') {
      steps {
        git(url: 'https://github.com/Millanjena1/NEWBLUW.git', branch: '*')
      }
    }

  }
}