pipeline {
    agent none 
    stages {
        stage('Build') {
            steps {
				script {
					echo 'Hello, Maven'
					bat "npm start"
				}
            }
        }
    }
}