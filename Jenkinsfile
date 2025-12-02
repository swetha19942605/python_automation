pipeline {
    agent any
    stages {
        stage('version') {
            steps {
                // Corrected: Using 'bat' for Windows command execution
                bat 'C:\Users\VNRM37\AppData\Local\Programs\Python\Python310\python.exe --version' 
            }
        }
        stage('hello') {
            steps {
                // Corrected: Using 'bat' for Windows command execution
                bat 'C:\Users\VNRM37\AppData\Local\Programs\Python\Python310\python.exe wrapper.py' 
            }
        }
    }
}