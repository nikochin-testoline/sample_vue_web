pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh 'npm i vue'
      }
    }

    stage('Build') {
      steps {
        sh 'npm run build'
      }
    }

  }
  tools {
    nodejs 'NodeJS'
  }
}