pipeline {
    agent any
    stages {
        stage("Hello") {
            steps {
                echo 'Hello, Sending Commit request from git hub webhook'
                sh "ls -lrth"
            }
        }
    }
}
