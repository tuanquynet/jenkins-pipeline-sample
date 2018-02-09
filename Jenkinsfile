pipeline {
  agent any
  stages {
    stage('Build') {
      agent {
        node {
          label 'nodejs-env'
        }
        
      }
      steps {
        sh 'node --version'
      }
    }
  }
}