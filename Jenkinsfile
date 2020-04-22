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
                sh 'npm run install'
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