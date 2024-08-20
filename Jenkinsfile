pipeline {
    agent agent1
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
