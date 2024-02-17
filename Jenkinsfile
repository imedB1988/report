pipeline {
  agent any
  stages {
    stage('run test ') {
      steps {
        sh 'cd curriculum-back && npm install vue-jest && npm install && npm run test:unit'
      }
    }

  }
}