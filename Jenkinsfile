pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
		sh "cd $C:\Users\pnarang\Documents\GitHub\QuarantineDemo"
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
		sh "npm run install"
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}