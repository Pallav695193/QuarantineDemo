pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sh 'cd /C/Users/pnarang/Documents/GitHub/QuarantineDemo'
        sh 'npm run ng -- build --base-href=/angular/'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing..'
        sh 'npm run lint'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }

  }
}