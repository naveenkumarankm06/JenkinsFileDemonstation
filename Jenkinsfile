pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Buildling an application'
          }
        }

        stage('Test') {
          steps {
            echo 'Tesing the application'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy an application'
      }
    }

  }
}