pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'building the application...'
            }
        }
        
        stage('Test') {
            steps {
                echo 'testing the application...'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'deploying the application...'
            }
        }
    }
    
    post {
        success {
            echo 'Successfull'
        }
        failure {
            echo 'Failed'
        }
    }
}

