pipeline {
    agent any

    stages {
        stage('version') {
            steps {
                sh 'python3 --version'
            }
        }
        stage('hellow') {
            steps {
                sh 'python3 hello.py'
            }
        }       
    }
}