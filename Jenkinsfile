pipeline {
  agent {
    node {
      label 'doit'
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