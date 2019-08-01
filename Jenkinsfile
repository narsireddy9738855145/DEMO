
pipeline {
  agent any
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello Mr Narsi Reddy welcome to Jenkins'
      }
    }
    stage('Proceed') {
      steps {
        echo input('Do you want to proceed?')
        echo 'Approved'
      }
    }
  }
}
