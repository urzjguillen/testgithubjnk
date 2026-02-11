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
                sh 'git clone git@github.com:urzjguillen/testgithubjnk.git'
            }
        }
    }
}
