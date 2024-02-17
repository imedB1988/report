pipeline {
  agent any
  stages {
    stage('run test ') {
      steps {
        sh 'npm install vue-jest && npm install && npm run test:unit'
      }
    }

  }
}