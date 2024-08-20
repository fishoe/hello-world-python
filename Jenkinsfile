pipeline {
    agent docker {
        image 'python:3.12.5-alpine3.20'
        label 'ubuntu-22.04'
        args  '-v /tmp:/tmp'
    }

    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('test') {
            steps {
                sh 'python main.py'
            }
        }
    }
}
