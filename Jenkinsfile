pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'BUILD.bat', returnStdout: true)
      }
    }
  }
}