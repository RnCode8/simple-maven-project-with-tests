pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Running Build Stage...'
                sh 'echo Compiling source code'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Test Stage...'
                sh 'echo Executing tests'
            }
        }

        stage('Package') {
            steps {
                echo 'Packaging application...'
                sh 'echo Creating artifact'
            }
        }
    }

    post {
        success {
            echo 'Pipeline completed successfully!'
        }
    }
}
