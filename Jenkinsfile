pipeline {
    agent any

    options {
        timestamps()
    }

    stages {

        stage('Build') {
            steps {
                echo "Building ..."
            }
        }

        stage('Test') {
            steps {
                echo "Running test..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying the app..."
            }
        }

    }

    post {
        success {
            echo "Pipeline executed successfully!"
        }
        failure {
            echo "Pipeline failed. Please check logs."
        }
    }
}
