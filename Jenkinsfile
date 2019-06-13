pipeline {
  agent none
  stages {
    stage('Build') {
      steps {
        sleep 12
      }
    }
    stage('Speak') {
      steps {
        echo 'Hi'
      }
    }
    stage('') {
      steps {
        retry(count: 10)
      }
    }
  }
}