pipeline {
    agent any
 
    stages {
        stage('Build and Push Docker Image') {
            steps {
                script {
                    // Your Docker build and push commands here
                    sh 'docker build -t your-image .'
                    sh 'docker push your-image'
                }
            }
        }
    }
}
