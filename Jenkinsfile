pipeline {
    agent any

    environment {
        PATH = '/usr/local/bin/node'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh '''
                node -v
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