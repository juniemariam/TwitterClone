/* Requires the Docker Pipeline plugin */
pipeline {
    agent {
        label 'windows' // assuming you have a Windows agent
    }
    stages {
        stage('Install Node.js') {
            steps {
                bat 'npm install'
            }
        }
        stage('Test') {
            steps {
                bat 'node --version'
            }
        }
    }
}

