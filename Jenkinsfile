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
<<<<<<< HEAD
}
=======
}
>>>>>>> 90fec1d8a34c7203e3f3b3a1be5bc340ceb6869a
