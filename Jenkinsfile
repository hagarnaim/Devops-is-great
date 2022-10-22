pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Run') {
            steps {
                sh '''docker-compose up'''
            }
        }
    }
}
