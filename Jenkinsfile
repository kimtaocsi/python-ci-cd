pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        sh 'build_tag = sh(returnStdout: true, script: \'git rev-parse --short HEAD\').trim()'
      }
    }

  }
}