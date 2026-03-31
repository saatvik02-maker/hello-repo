pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Code pulled from GitHub"
            }
        }

        stage('Build') {
            steps {
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                sh 'cat texxtfile.js'
            }
        }
    }
}
