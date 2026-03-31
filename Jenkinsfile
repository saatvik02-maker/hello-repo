pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Code fetched from GitHub"
            }
        }

        stage('Build') {
            steps {
                echo "Running Hello World build"
                sh 'echo Hello World from Jenkins Pipeline'
            }
        }

        stage('Verify') {
            steps {
                echo "Listing files in workspace"
                sh 'ls -l'
            }
        }
    }
}
