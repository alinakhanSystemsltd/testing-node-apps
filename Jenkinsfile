pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'hello world '
            sh 'echo how are you'
            archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
          }
        }

        stage('Test') {
          steps {
            sh 'echo test this file '
          }
        }

      }
    }

  }
}