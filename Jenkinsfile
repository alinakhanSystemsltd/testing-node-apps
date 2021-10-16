pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build'
            echo 'Bees Buzz!'
          }
        }

        stage('Test') {
          steps {
            echo 'testing'
            echo 'bees bees!!!'
            sh 'sleep 5'
            sh 'echo success!!!'
          }
        }

        stage('Deploy') {
          steps {
            echo 'deploy it'
          }
        }

        stage('Ayesha ') {
          steps {
            echo 'Hello Ayesha '
          }
        }

      }
    }

  }
}