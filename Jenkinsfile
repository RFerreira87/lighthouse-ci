pipeline {
  agent any
  stages {
    stage('começando') {
      agent {
        docker {
          image 'jenkins/agent'
        }

      }
      steps {
        echo 'teste'
      }
    }

    stage('sleep') {
      steps {
        sleep 15
      }
    }

    stage('error') {
      steps {
        sh 'echo bananas'
      }
    }

  }
}