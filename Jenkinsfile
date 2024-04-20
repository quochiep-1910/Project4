pipeline {
    agent any
    options {
        // Set user to root
        user 'root'
    }
    stages {
        stage("Build Docker Image") {
            steps {
                script {
                    // Ensure Docker daemon is running and accessible
                    sh 'whoami'
                    sh 'docker --version'
                }
            }
        }
    }
}
