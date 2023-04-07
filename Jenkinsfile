pipeline {
    agent any 
    
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building feature-01 branch..."'
            }
        }
        
        stage('Test') {
            steps {
                // Commentaire
                sh 'echo "Testing feature-01 branch..."'
            }
        }
        
        stage('Deploy') {
            steps {
                sh 'echo "Deploying feature-01 branch..."'
            }
        }
    }
}