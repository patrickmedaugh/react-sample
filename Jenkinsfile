pipeline {
    agent { docker { image 'node:8.11.3' } }
    stages {
        stage('build') {
            steps {
                sh 'npm build'
            }
        }
        stage('test') {
            steps {
                sh 'npm test'
            }
        }
    }
}