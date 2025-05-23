pipeline {
    agent any
    stages {
        stage('Ubuntu container') {
            agent { 
                docker { images 'ubuntu:latest' }
            }
        }
    stage('Hello world') {
            agent {
                docker { images 'Helloworld:latest' }
            }
        }
    stage('Python') {
            agent {
                docker { images 'python:latest' }
            }
        }
    }
}
