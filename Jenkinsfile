pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git(
                    branch: 'main',
                    url: 'https://github.com/altaf-khan-jk/lab2-Jenkins-CI-CD.git',
                    credentialsId: 'github-token'
                )
            }
        }

        stage('Build') {
            steps {
                echo "Building project..."
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
    }

    post {
        success {
            echo "Pipeline completed successfully!"
        }
        failure {
            echo "Pipeline failed!"
        }
    }
}
