pipeline {
  agent any
  stages {
    stage('Build code') {
      steps {
        sh 'cd my-app && mvn deploy'
      }
    }

    stage('post build shell script') {
      steps {
        sh 'echo "Build is successful"'
      }
    }

  }
}