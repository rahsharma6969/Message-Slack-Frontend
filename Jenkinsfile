
pipeline {
    agent any

    stages {
        stage('First Pipeline') {
            steps {
                echo 'Hello from Jenkins!'
                echo 'My MERN messaging app CI pipeline has started.'
            }
        }

        stage('Simulate a Test Failure') {
            steps {
                echo 'Running a simulated test...'
                error 'Simulated test failure!'
            }
        }

        stage('Build Application') {
            steps {
                echo 'Building the application...'
            }
        }
    }
}
