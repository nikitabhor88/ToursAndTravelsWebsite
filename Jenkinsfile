pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'echo "Compiling"'
      }
    }

    stage('Test') {
      agent any
      steps {
        bat 'echo "Running Tests"'
      }
    }

  }
}