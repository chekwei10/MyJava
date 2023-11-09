pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Hi'
          }
        }

        stage('Build2') {
          steps {
            echo 'hello'
          }
        }

      }
    }

  }
}