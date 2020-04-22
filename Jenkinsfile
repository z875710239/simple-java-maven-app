pipeline {
  agent any
  stages {
    stage('Echo1') {
      parallel {
        stage('Echo1') {
          steps {
            echo 'Hello'
          }
        }

        stage('Echo2') {
          steps {
            echo 'Word'
          }
        }

      }
    }

    stage('sleep') {
      steps {
        sleep 2
      }
    }

    stage('End') {
      steps {
        echo 'end'
      }
    }

  }
}