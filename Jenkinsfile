pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'echo hello world'
                bat 'javac Hello.java'
                bat 'java Hello'
            }
        }
    }
}
