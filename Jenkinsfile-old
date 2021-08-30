pipeline {
    agent any
    stages {
        stage('create') {
            steps {
               sh "mkdir test100"
            }
        }
        stage('copy') {
            steps {
                sh "cp -r test100 test200"
            }
        }
        stage('remove') {
            steps {
                sh "rm -rf test200"
            }
        }
        stage('rename') {
            steps {
                sh "mv test100 test200"
            }
        }
    }
}
