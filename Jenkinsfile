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
        sh 'npm cache clean -f && rm -rf node_modules && npm i'
      }
    }

    stage('test') {
      steps {
        sh 'npm run test:unit'
      }
    }

  }
}