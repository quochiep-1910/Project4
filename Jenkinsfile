pipeline {
    agent any

    stages {
        stage("Build Docker Image") {
            steps {
                script {
                    // Ensure Docker daemon is running and accessible
                    sh 'docker --version'
                }
            }
        }
    }
}
