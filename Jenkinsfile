pipeline {
    agent any

    stages {

        stage('Clone Info') {
            steps {
                echo "Running on branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Build') {
            steps {
                echo "Building application..."
            }
        }

        stage('Test') {
            steps {
                echo "Testing application..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }
    }
}
