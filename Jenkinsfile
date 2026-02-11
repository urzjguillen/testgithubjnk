pipeline{
    agent{
        node{
            label 'agent001'
        }
    }
    stages{
        stage('checkout'){
            steps{
                checkout scm
            }
        }
        stage('Test'){
            steps{
                sh 'ls -l'
            }
        }
    }
}
