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
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}