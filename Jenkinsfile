pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        nodejs(nodeJSInstallationName: 'NodeJS') {
          sh 'npm config ls'
        }
      }
    }

  }
}
