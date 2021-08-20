pipeline {
    agent any
    stages {
        stage('create') {
            steps {
               sh "mkdir test111"
            }
        }
        stage('copy') {
            steps {
                sh "cp -r test111 test1111"
            }
        }
        stage('remove') {
            steps {
                sh "rm -rf test1111"
            }
        }
        stage('rename') {
            steps {
                sh "mv test111 test2"
            }
        }
    }
}
