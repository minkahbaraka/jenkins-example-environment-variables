pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
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
}