
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code is managed in GitHub.'
            }
        }

        stage('Build') {
            steps {
                echo 'Build stage is ready.'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage is ready.'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }

        failure {
            echo 'Pipeline failed. Check the console logs.'
        }
    }
}
