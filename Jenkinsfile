pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                sh 'python -c "print(\"Hello\")"'
            }
        }
    }
}
