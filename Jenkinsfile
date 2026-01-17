pipeline {
  agent any

  stages {
    stage('Checkout') {
      steps {
        checkout scm
        sh 'ls -la'
      }
    }

    stage('Hello') {
      steps {
        echo "WORKSPACE is: ${env.WORKSPACE}"
        sh 'echo "Shell WORKSPACE is: $WORKSPACE"'
        echo "THIS WOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOOORKS ***********************************"
      }
    }
  }
}
