pipeline {
    agent any

    stages {
        stage('Docker Image Build') {
            steps {
                echo 'Hello Build'
                sh "pwd"
                sh '''
                ls
                date '''
            }
        }
        stage('Docker Image Publish') {
            steps {
                echo 'Hello Build'
            }
        }
        stage('Deploy in Dev Environment') {
            steps {
                echo 'Hello Dev'
            }
        }
        stage('Deploy in Prod Environment') {
            steps {
                echo 'Hello Prod'
            }
        }
    }
}
