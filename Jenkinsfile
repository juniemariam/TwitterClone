pipeline {
    agent any
    
    stages {
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Use bat for Windows to run the Gradle Wrapper
                bat 'gradlew.bat check' // Change to 'gradlew check' if using WSL
            }
        }
    }

    post {
        always {
            echo 'Archiving test results...'
            // Adjust the path if your reports are in a different location
            junit '**/build/test-results/test/*.xml' // Default Gradle report path for tests
        }
    }
}





