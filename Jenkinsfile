pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                // Corrected: Using 'bat' for Windows command execution
                bat 'python --version' 
            }
        }
        stage('hello') {
            steps {
                // Corrected: Using 'bat' for Windows command execution
                bat 'python wrapper.py' 
            }
        }
    }
}