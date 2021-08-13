pipeline {
    agent any
    
    stages {
        stage('Checking Version') {
            steps {
                bat 'java -version'
            }
        }
        stage('Compiling') {
            steps {
                bat 'javac Hello.java'
            }
        }
        
        stage('Running') {
            steps {
                bat 'java Hello'
            }
        }
    }
}
