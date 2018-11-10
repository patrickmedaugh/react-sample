pipeline {
    agent any
    environment {
        PATH='/usr/local/bin'
    }
    stages {
        stage('build') {
            steps {
                sh 'npm run build'
            }
        }
        stage('test') {
            steps {
                sh 'npm run test'
            }
        }
    }
}