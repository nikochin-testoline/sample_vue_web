pipeline {
  agent any
  stages {
    stage('Build') {
      nodejs(nodeJSInstallationName: 'Node 6.x') {
        sh 'npm config ls'
      }
    }

  }
}
