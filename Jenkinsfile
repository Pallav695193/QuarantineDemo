pipeline {
    agent any

    environment {
        PATH = '/usr/local/bin/node'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh '''
			 	npm install
			 	'''
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