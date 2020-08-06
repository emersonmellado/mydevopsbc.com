pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "This is our BUILD stage"
                sh 'ls -la'
            }
        }
        stage('Test') {
            steps {
                echo "This is our TEST stage"
            }
        }
        stage('Deploy') {
            steps {
                echo "This is our DEPLOY stage"
            }
        }        
    }
}
