/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.13.0a4-windowsservercore-ltsc2022' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}