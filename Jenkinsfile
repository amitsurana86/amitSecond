pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
				parallel {
					a: {
							script {
								echo 'Hello, Amit First'
								bat "npm start"
							}
					}
					b: {
							script {
								echo 'Hello Amit Second'
								bat "npm start"
							}
					}
				}
            }
        }
    }
}