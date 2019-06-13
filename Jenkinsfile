pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sleep 12
      }
    }
    stage('Speak') {
      parallel {
        stage('Speak') {
          steps {
            echo 'Hi'
          }
        }
        stage('') {
          steps {
            echo 'Whats good'
          }
        }
      }
    }
  }
}