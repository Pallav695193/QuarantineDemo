pipeline {
  agent {
   node {label 'nodejs'}
  }
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        sh 'npm install -g @angular/cli@latest -ddd'
      }
    }

    stage('Test') {
      steps {
        echo 'Testing..'
		sh 'npm run --ng test'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }

  }
}