pipeline {
  agent {
    node {
      label 'Windows'
    }

  }
  stages {
    stage('Build') {
      steps {
        bat(script: 'BUILD.bat', returnStdout: true)
      }
    }
  }
}