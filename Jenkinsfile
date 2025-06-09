pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                ech0 'mkreddy,,,...,,,,'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            when {
                branch 'main'
            }
            steps {
                echo 'Deploying to production...'
            }
        }
    }
}
