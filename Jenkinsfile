pipeline {
    agent { docker { image 'python:3.6.9-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
