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
		 	npm install --verbose -d 
		 	npm install --save classlist.js
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