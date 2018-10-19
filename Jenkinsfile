pipeline {
  agent none
  stages {
    stage('Test') {
      steps {
        sh 'npm install'
        sh 'robot -i test .'
      }
    }
  }
}