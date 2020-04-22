pipeline {
    agent any

    environment {
        PATH = 'C:\Program Files (x86)\Jenkins\nodes'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh '''
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