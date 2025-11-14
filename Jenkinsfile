pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/MinhSei/Test-Pipeline', branch: 'main')
      }
    }

    stage('Front-End Test') {
      steps {
        sh 'ls -la'
        git 'https://github.com/MinhSei/Test-Pipeline'
      }
    }

  }
}