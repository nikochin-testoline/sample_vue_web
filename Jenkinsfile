pipeline {
  agent any
  
  tools {nodejs "NodeJS"}
  
  stages {
    stage('Build') {
      steps {
        sh '''npm config ls
npm run build'''
      }
    }

  }
}
