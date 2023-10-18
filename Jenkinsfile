pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        
        stage('Build') {
            steps {
                sh 'echo "Building the code"'
            }
        }
        
        stage('Test') {
            steps {
                sh 'echo "Running tests"'
            }
        }
    }
}