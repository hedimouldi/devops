pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'echo "Compilation started at $(date)"'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "Tests passed: 3/3"'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                sh 'echo "Deployed successfully"'
            }
        }
    }
}
