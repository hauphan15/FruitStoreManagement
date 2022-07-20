pipeline {
    agent any
    stages {
        stage('Run app') {
            steps {
                bat 'npm install'
                bat 'npm start'
            }
        }
    }
}