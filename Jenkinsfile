pipeline {
  agent { docker { image 'node:12' } }
  stages {
    stage('build') {
      steps {
        sh 'npm --version'
      }
    }
  }
}
