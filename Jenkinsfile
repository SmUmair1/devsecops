pipeline {
    agent any

    stages {
        stage('Build and Push Docker Image') {
            steps {
                script {
                    docker.withDockerServer('tcp:///var/run/docker.sock:2376') {
                        // Your Docker build and push commands here
                        sh 'docker build -t dockerfile:latest .'
                    }
                }
            }
        }
    }
}
