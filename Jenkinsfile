pipeline {
    agent any

    stages {
        stage('Run Tests') {
            steps {
                echo 'Running tests...'
                // Here we run a simple test script (replace this with your actual test command)
                bat 'echo Running some tests > test_results.txt' // Simulate a test command
                bat 'echo Test results: All tests passed >> test_results.txt' // Simulate test results
            }
        }
    }

    post {
        always {
            echo 'Archiving test results...'
            // Archive the test results file
            archiveArtifacts artifacts: 'test_results.txt', fingerprint: true
            // Optionally, you can display the contents of the test results file
            bat 'type test_results.txt'
        }
    }
}






