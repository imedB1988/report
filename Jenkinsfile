pipeline {
  agent any
  stages {
    stage('run test') {
      steps {
        sh 'cd curriculum-back && npm install && npm run test'
      }
    }

  }
}