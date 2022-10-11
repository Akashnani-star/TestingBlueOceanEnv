pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        sh 'echo $swaggerChecks'
      }
    }

  }
  environment {
    swaggerChecks = 'DISABLE'
  }
}