pipeline {
    agent any
    stages {
        stage('NPM Install') {
            steps {
                npm install
            }
        }
        stage('Run integration tests') {
            steps {
                npm run test
            }
        }
    }
}