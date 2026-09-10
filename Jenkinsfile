pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out local codebase...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'git status'
            }
        }
        stage('Test') {
            steps {
                echo 'Running automated tests...'
            }
        }
    }
    post {
        always {
            echo 'Pipeline execution finished!'
        }
    }
}
