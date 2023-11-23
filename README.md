pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Your build commands (e.g., compiling code)
            }
        }
        stage('Test') {
            steps {
                // Your testing commands (e.g., running unit tests)
            }
        }
        stage('Deploy') {
            steps {
                // Your deployment commands (e.g., deploying to a server)
            }
        }
    }
}
