pipeline {
    agent any
 
    stages {
 
        stage('Checkout') {
            steps {
                echo 'Checking out Employee Leave project'
            }
        }
 
        stage('Build') {
            steps {
                echo 'Build stage completed'
            }
        }
 
        stage('Test') {
            steps {
                bat 'findstr /I "<html" index.html'
            }
        }
 
        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }
}
 
