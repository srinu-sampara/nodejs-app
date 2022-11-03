pipeline {
    agent any
    stages {
        stage('Creating Docker Image') {
            steps {
                echo 'Building Docker Image'
                sh 'docker build -t nodejs-app .'
            }
        }
        stage('compose up') {
            steps {
                echo 'bringingup node and sql container'
                sh 'docker compose up -d '
            }
        }
    }
}