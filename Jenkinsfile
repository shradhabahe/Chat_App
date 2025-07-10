pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    // Compile and build the Java WebSocket server
                    sh 'javac ChatServer.java'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Optional: Add your test cases here if required
                    echo 'Running tests...'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Here you would deploy the application (e.g., by starting the server)
                    echo 'Deploying Chat App'
                }
            }
        }
    }
}
