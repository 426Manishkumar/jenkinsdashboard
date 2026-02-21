
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Checking out code..."
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Build stage executed successfully."
            }
        }

        stage('Run') {
            steps {
                echo "Application executed successfully."
            }
        }
    }
}
