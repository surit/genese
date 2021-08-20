pipeline {
    agent any
    stages {
        stage('create') {
            steps {
               sh "mkdir test1"
            }
        }
        stage('copy') {
            steps {
                sh "cp test1 test11"
            }
        }
        stage('remove') {
            steps {
                sh "rm test11"
            }
        }
        stage('rename') {
            steps {
                sh "mv test1 test2"
            }
        }
    }
}
