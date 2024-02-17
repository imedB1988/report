pipeline {
  agent any
  stages {
    stage('run test') {
      steps {
        sh 'cd curriculum-front && npm install && npm test'
      }
    }

  }
}