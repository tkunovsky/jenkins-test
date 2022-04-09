pipeline {
    agent { label 'python' }
    stages {
        stage('build') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('Test') {
            steps {
                sh python3 -c print('Hello World')
            }
        }
    }
}
