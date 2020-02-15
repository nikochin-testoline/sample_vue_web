pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        nodejs('NodeJS') {
          sh 'npm config ls'
        }

        sh 'npm run build'
      }
    }

  }
}