pipeline {
    agent { docker { image 'node:8.16.0-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'echo test message'
            }
        }
    }
}