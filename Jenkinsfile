pipeline {
    agent any
    stages {
        stages('Install package') {
            steps {
                bat 'npm install'
            }
        }
        stages('Run app') {
            steps {
                bat 'npm start'
            }
        }
    }
}