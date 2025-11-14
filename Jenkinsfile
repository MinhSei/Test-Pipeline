pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building...'
        git(url: 'https://github.com/MinhSei/Test-Pipeline', branch: 'main')
      }
    }

    stage('Test') {
      steps {
        echo 'Testing...'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying...'
      }
    }

  }
}