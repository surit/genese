
pipeline {
    agent any

    stages {
        stage('pwd') {
            steps {
                sh 'pwd'
            }
        }
    }
    
    stages {
        stage('whoami') {
            steps {
                sh 'whoami'
            }
        }
    }
    
    stages {
        stage('get pods') {
            steps {
                sh 'kubectl get pods'
            }
        }
    }
    
    stages {
        stage('scale') {
            steps {
                sh 'kubectl scale deployment metrics-server -n kube-system --replicas=2'
            }
        }
    }
}
