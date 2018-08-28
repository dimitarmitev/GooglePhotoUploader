pipeline {
  agent any
  stages {
    stage('Sleep') {
      steps {
        sleep(time: 10, unit: 'SECONDS')
      }
    }
    stage('End') {
      steps {
        echo 'End'
      }
    }
  }
}