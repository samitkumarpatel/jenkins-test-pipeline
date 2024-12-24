pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') {
            steps {
                sh 'ls -al'
            }
        }
        stage('Test'){
            steps {
                sh 'echo "Hello World"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Hi"' //
            }
        }
    }
}
