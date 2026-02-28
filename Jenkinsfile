pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Starting Build Stage...'
                sh 'echo Compiling application...'
                echo 'Build Stage Complete → Triggering Test Stage'
            }
        }

        stage('Test') {
            steps {
                echo 'Starting Test Stage...'
                sh 'echo Running tests...'
                echo 'Test Stage Complete'
            }
        }
    }
}
