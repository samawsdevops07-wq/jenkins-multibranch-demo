pipeline {
    agent any

    stages {
        stage('Branch Info') {
            steps {
                echo "Running on branch: ${env.BRANCH_NAME}"
            }
        }

        stage('Build') {
            steps {
                echo "Building application..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying from ${env.BRANCH_NAME}"
            }
        }
    }
}
