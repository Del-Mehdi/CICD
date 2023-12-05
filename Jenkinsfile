pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/Del-Mehdi/CICD.git', branch: 'main', poll: true, changelog: true)
      }
    }

    stage('build') {
      steps {
        echo 'Change deteted in the pipline'
      }
    }

  }
}