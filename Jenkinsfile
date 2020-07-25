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
                bat script : 'echo Hello Kodi'
            }
        }    
        stage('Deploy') {
            steps {
                    bat script: 'npm start'
            }
        }
    }
}
