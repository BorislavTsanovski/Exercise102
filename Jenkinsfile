pipeline {
    agent any
    stages {
        stage('NPM Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Run integration tests') {
            steps {
                sh 'npm run test'
            }
        }
    }
}