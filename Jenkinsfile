pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                    bat script: 'npm install'
            }
        }
        stage('Deploy') {
            steps {
                    bat script: 'npm start'
            }
        }
    }
}
