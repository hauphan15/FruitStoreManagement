pipeline {
    agent any
    stages {
        stages('Run app') {
            steps {
                bat 'npm install'
                bat 'npm start'
            }
        }
    }
}