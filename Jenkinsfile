pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      parallel {
        stage('Buzz Buzz') {
          steps {
            echo 'Bees Buzz!'
          }
        }

        stage('error') {
          steps {
            echo 'Bees Buzz!!!'
          }
        }

      }
    }

  }
}