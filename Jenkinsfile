pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/segbeyon24/dashboard', branch: 'main')
      }
    }

    stage('lists') {
      steps {
        sh 'ls -la'
      }
    }

  }
}