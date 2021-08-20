pipeline {
    agent any
    stages {
        stage('create') {
            steps {
               sh "mkdir test11"
            }
        }
        stage('copy') {
            steps {
                sh "cp -r test11 test111"
            }
        }
        stage('remove') {
            steps {
                sh "rm test111"
            }
        }
        stage('rename') {
            steps {
                sh "mv test11 test2"
            }
        }
    }
}
