pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        bat(script: 'echo "hi"', returnStdout: true, returnStatus: true)
        build 'my job'
      }
    }

  }
}