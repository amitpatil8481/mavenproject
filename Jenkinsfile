pipeline {
  agent any
  stages {
    stage('Build code') {
      steps {
        sh 'cd my-app && mvn install'
      }
    }

  }
}