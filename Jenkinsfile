pipeline {
    agent {
        docker {
            image 'python:3.10-slim'
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
