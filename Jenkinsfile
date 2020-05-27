pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'npm install'
      }
    }
    stage('deliver') {
      steps {
        sh 'npm run start'
      }
    }
  }
}
