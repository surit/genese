pipeline {
    agent any

    stages {
        stage('pwd') {
            steps {
                sh 'pwd'
            }
        }
    
        stage('whoami') {
            steps {
                sh 'whoami'
            }
        }
    
        stage('get pods') {
            steps {
                sh 'kubectl get pods'
            }
        }
    
        stage('scale') {
            steps {
                sh 'kubectl scale deployment metrics-server -n kube-system --replicas=2'
            }
        }
    }
 }

