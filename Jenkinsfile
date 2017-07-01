pipeline {
  agent any
  stages {
    stage('Print1') {
      steps {
        sh 'echo Hello World'
      }
    }
    stage('Approval') {
      steps {
        input 'Do you want to got to next step'
      }
    }
    stage('Print2') {
      steps {
        echo 'Print2'
      }
    }
  }
}