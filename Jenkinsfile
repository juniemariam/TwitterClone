/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    tools {
        nodejs 'NodeJS 22.x'  // Specify the Node.js installation
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





