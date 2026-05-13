pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building frontend-app..." && sleep 2'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing frontend-app..." && sleep 3'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying frontend-app to staging..." && sleep 1'
            }
        }
    }
}
// Changes for develop
