pipeline {
    agent any

    stages {
        // Stage 1: Install project dependencies
        stage('Install Dependencies') {
            steps {
                echo 'Installing Node.js dependencies...'
                bat 'npm install'
            }
        }

        // Stage 2: Run tests
        stage('Test') {
            steps {
                echo 'Running tests...'
                bat 'npm test'
            }
        }
    }
}
