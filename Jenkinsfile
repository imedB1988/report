pipeline {
  agent any
  stages {
    stage('change directory') {
      steps {
        sh 'cd curriculum-front'
      }
    }

    stage('install dependencies') {
      steps {
        sh 'npm install'
      }
    }

    stage('test') {
      steps {
        sh 'npm run test:unit'
      }
    }

  }
}