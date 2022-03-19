pipeline {
  agent any
  stages {
    stage('Build code') {
      steps {
        sh 'cd myapp && mvn install'
      }
    }

  }
}