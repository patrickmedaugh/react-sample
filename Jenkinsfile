pipeline {
    agent any
    environment {
        PATH='/usr/local/bin'
    }
    stages {
        stage('lint') {
            steps {
                sh 'npm run lint'
            }
        }
        stage('test') {
            steps {
                sh 'npm run test'
            }
        }
    }
}