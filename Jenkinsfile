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
          }
        }

      }
    }

  }
}