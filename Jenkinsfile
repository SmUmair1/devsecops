pipeline {
    agent any
     environment {
        PATH = "/var/jenkins_home"
    }
    stages {
        stage('Build and Push Docker Image') {
            steps {
                script {
                    // Your Docker build and push commands here
                    sh 'docker build -t dockerfile:latest .'
                }
            }
        }
    }
}
