/* Requires the Docker Pipeline plugin */
pipeline {
    agent {
        label 'windows'
    }
    stages {
        stage('Test') {
            steps {
                bat 'node --version'
            }
        }
    }
}
