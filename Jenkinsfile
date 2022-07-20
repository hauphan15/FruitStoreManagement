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
    post {
        always {
            echo 'Buil app has completed'
        }
        success {
            echo 'Build app successfully'
        }
        failure {
            echo 'Build app failed'
        }
    }
}