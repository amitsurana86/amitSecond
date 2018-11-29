pipeline {
    agent none 
    stages {
        stage('Build') {
            steps {
                echo 'Hello, Maven'
                bat "npm install"
            }
        }
    }
}