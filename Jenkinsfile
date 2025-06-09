pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                echo 'mkreddy,,,...,,,,'
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
