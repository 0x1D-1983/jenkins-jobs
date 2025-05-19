pipeline {
    agent {
        docker {
            image 'python:3.10-slim'
            label 'docker'    // Optional: if you have node labeling
            args '-v /tmp:/tmp' // Optional Docker run arguments
        }
    }
    stages {
        stage('Run Python') {
            steps {
                sh 'python --version'
            }
        }
    }
}
