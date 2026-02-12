pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Checkout the source code from the repository
                checkout scm
                echo 'Building the project...'
                // Add your build commands here (e.g., sh 'npm install', sh 'make')
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add your test commands here (e.g., sh 'npm test')
            }
        }
    }
}
