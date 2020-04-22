pipeline {
    agent any

    environment {
        PATH = '/usr/local/bin/node'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
			sh '''
		 	npm install --verbose -d 
		 	npm install --save classlist.js
		 	'''
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}