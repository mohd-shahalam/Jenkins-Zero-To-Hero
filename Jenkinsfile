pipeline {
    agent {
        docker {
            image 'node:16-alpine'  // Docker image to use
            args '-v /tmp:/tmp'     // Optional Docker arguments
        }
    }
    stages {
        stage('Build') {
            steps {
                // Example commands within the Docker container
                sh 'node --version'
                sh 'npm --version'
            }
        }
    }
}
