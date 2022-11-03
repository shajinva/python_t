cat <<-'JENKINSFILE' > Jenkinsfile
pipeline {
  agent { docker { image 'python:3.7.2' } }
  stages {
    stage('build') {
      steps {
        sh 'pip install -r requirements.txt'
      }
    }
     stage('version') {
      steps {
        sh 'python --version'
      }
    }
     stage('hello') {
      steps {
        sh 'python hello.py'
      }
    }
  }
}
JENKINSFILE
