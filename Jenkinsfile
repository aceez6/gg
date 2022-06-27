pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent {
                docker {
                    image 'python:3.6.9-alpine' 
                }
            }
            steps {
                sh 'python -- version'
            }
        }
    }
}
