pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Anjali-sahu830/myremoap.git'
            }
        }
        stage('Build') {
            steps {
               bat 'Hello.java'
            }
        }
        stage('Execute') {
            steps {
                bat 'Hello'
            }
        }
    }
}
