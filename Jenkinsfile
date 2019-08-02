
pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Hello Mr Narsi Reddy welcome to Jenkins'
      }
    }
    stage('Test') {
      steps {
        echo input('Do you want to proceed?')
        echo 'Approved'
      }
    }
    stage('Deploy') {
      steps {
        echo input('Shall I Approve your Changes?')
        echo  'yes'
      }
    }
    stage('Complete') {
      steps {
        echo 'Completed Deployment Process'
      }
    }
  }
}
