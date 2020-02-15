pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        nodejs('NodeJS') {
          sh '''npm config ls
npm run build'''
        }

      }
    }

  }
}