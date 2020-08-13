pipeline {
  agent any
  stages {
    stage('Buzz Buzz') {
      steps {
        sh './jenkins/build.sh'
      }
    }

    stage('Bees Buzz Test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}