pipeline {
    agent any 
    
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building testing branch..."'
            }
        }
        
        stage('Test') {
            steps {
                // Commentaire
                sh 'echo "Testing testing branch..."'
            }
        }
        
        stage('Deploy') {
            steps {
                sh 'echo "Deploying testing branch..."'
            }
        }
    }
}