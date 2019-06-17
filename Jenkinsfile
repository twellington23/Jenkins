pipeline {
  agent none
  stages {
    stage('Sleep') {
      steps {
        sleep 10
      }
    }
    stage('Speak') {
      steps {
        echo 'Hi'
      }
    }
    stage('Sleep Again') {
      steps {
        sleep 5
      }
    }
  }
}