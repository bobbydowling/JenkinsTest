/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.12.2-bookworm' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}