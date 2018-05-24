pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'We\'re building'
      }
    }
    stage('Test') {
      steps {
        echo 'We\'re testing'
      }
    }
    stage('Deploy') {
      steps {
        echo 'We\'re deploying!'
      }
    }
    stage('Notify') {
      steps {
        publishEvent simpleEvent('helloWorld')
      }
    }
  }
}