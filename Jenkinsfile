pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                echo "Cloning repo..."
            }
        }

        stage('Build') {
            steps {
                echo "No build required (static app)"
            }
        }

        stage('Deploy') {
            steps {
                sh '''
                sudo cp -r * /var/www/html/
                '''
            }
        }
    }
}
