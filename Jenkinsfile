
pipeline {
    agent any

    stages {
        stage('Check Git') {
            steps {
                bat 'git --version'
            }
        }

        stage('Check Node and npm') {
            steps {
                bat 'node --version'
                bat 'npm --version'
            }
        }
    }
}
