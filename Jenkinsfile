/* Requires the Docker Pipeline plugin */
pipeline {
    agent any  // Use any available agent
    stages {
        stage('Install Node.js') {
            steps {
                sh 'npm install'  // Replace 'bat' with 'sh' for Linux agents
            }
        }
        stage('Test') {
            steps {
                sh 'node --version'  // Replace 'bat' with 'sh' for Linux agents
            }
        }
    }
}





