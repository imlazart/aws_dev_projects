pipeline {
    agent any
    stages {
        stage('Checkout Code') {
            steps {
                // Checkout code from the repo
                git clone
            }
        }
        stage('Build') {
            steps {
                // Build steps
            }
        }
        stage('Terraform Init') {
            steps {
                sh 'terraform init'
            }
        }
        stage('Terraform Apply') {
            steps {
                sh 'terraform apply -auto-approve'
            }
        }
    }
    post {
        always {
            // Cleanup steps or notifications
        }
    }
}
