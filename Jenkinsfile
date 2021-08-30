pipeline {
    agent any
    
     stages {
        stage('pwd') {
            steps {
                sh 'pwd'
            }
        }
         
      stages {
        stage('whoami') {
            steps {
                sh 'Whoami'
            }
        } 

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
