pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        echo "I am a ${BUZZ_NAME}"
        sh 'env | sort'
      }
    }

    stage('Print Message') {
      steps {
        echo 'Bees Buzz!'
      }
    }

    stage('Print Message 2') {
      steps {
        echo 'Bees Buzz Buzz!'
      }
    }

    stage('New Branch Test') {
      steps {
        echo 'This is a new branch!'
      }
    }

  }
  environment {
    BUZZ_NAME = 'Worker Bee'
  }
}