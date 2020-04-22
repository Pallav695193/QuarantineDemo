pipeline {
    agent {

    node {
        label 'nodejs'
    }
	}
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'node -v'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
				 sh 'npm -v'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
				sh 'ng build --prod'
            }
        }
    }
}