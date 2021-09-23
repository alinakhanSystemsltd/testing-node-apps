pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'hello world '
            sh 'echo how are you'
          }
        }

        stage('Test') {
          steps {
            sh 'echo test this file '
            junit '**/surefire-reports/**/*'
          }
        }

      }
    }

  }
}