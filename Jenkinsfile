pipeline {
  agent any
  stages {
    stage('run test ') {
      steps {
        sh 'cd curriculum-front && npm vue-jest && npm install && npm run test:unit'
      }
    }

  }
}