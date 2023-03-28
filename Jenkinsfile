pipeline {
  agent any
  stages {
    stage('Development') {
      steps {
        echo 'I want to Develop'
      }
    }

    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'I want to Build'
          }
        }

        stage('Test') {
          steps {
            echo 'I want to test'
          }
        }

        stage('Deploy') {
          steps {
            echo 'I want to Deploy'
          }
        }

      }
    }

  }
}