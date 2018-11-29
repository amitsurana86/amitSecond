pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
				parallel {
					stage('First') {
						{
							script {
								echo 'Hello, Amit First'
								bat "npm start"
							}
						} 
					}
					stage('Second')
						{
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
}