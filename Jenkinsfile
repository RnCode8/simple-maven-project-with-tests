pipeline {
    agent any

    stages {
        stage('Sleep Stage') {
            steps {
                echo 'Simulating long process...'
                sh 'sleep 1000'
            }
        }

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
    }
}
