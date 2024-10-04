/* Requires the Docker Pipeline plugin */
pipeline {
    agent {
        docker {
            image 'node:20.17.0-alpine3.20'
            args '-v C:/Users/rinku/.jenkins/workspace/My-pipeline_main:/workspace -w /workspace'

        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
