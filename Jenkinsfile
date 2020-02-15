pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh '''npm config ls
npm run build'''
          }
        }

        stage('Install') {
          steps {
            sh 'npm i -g vue'
          }
        }

      }
    }

  }
  tools {
    nodejs 'NodeJS'
  }
}