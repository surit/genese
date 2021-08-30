pipeline {
    agent any

    stages {
        stage('get pods') {
            steps {
                kubectl get pods
            }
        }
        stage('scale') {
            steps {
                Kubectl get all
            }
        }
    }
}
