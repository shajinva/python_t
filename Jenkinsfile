pipeline {
  agent {
    docker { image 'python:3.8-buster' }
   }
  stages {
    stage('install dependencies') {
        steps {
            script {
            sh """ pip install -r requirements.txt """
        }
        }
    }
     stage('hello') {
      steps {
        sh 'python hello.py'
      }
    }
   }
   
}

