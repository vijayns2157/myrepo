pipeline {
    agent any
    stages {
        stage('Ubuntu container') {
            agent { 
                docker { image 'ubuntu:latest' }
            }
        }
    stage('Hello world') {
            agent {
                docker { image 'Helloworld:latest' }
            }
        }
    stage('Python') {
            agent {
                docker { image 'python:latest' }
            }
        }
    }
}
