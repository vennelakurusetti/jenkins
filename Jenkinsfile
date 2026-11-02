pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Fetching source code from GitHub'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building the application'
            }
        }

        stage('Test') {
            steps {
                bat 'echo Testing the application'
            }
        }

        stage('Deploy') {
            steps {
                bat 'echo Deploying the application'
            }
        }
    }
}
