pipeline {
    agent any

    stages {
        stage('Click') {
            steps {
                sh 'python3 click.py'
            }
        }
        stage('Welcome') {
            steps {
                sh 'python3 welcome.py'
            }
        }
    }
}

