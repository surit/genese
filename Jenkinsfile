pipeline {
    agent any

    stages {
        stage('get pods') {
            steps {
                sh 'kubectl get pods'
            }
        }
        stage('scale') {
            steps {
                sh 'kubectl get all'
            }
        }
    }
}
