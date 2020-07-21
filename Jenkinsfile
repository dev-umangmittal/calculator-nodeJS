pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                    bat script: 'npm install'
            }
        }
        stage('Test') {
            steps {
                    bat script: 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                    bat script: 'npm start'
            }
        }
    }
}
