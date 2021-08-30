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
                kubectl scale deployment metrics-server -n kube-system --replicas=2
            }
        }
    }
}
