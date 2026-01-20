pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
                sh 'node -v'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests'
            }
        }
    }
}
