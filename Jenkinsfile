pipeline{
    agent any
    stages{
        stage('pull code'){
            steps{
                git 'https://github.com/sathishgt07/python1.git'
            }
        
        }
        stage('check version'){
            steps{
                sh 'python3 --version'
            }
    
        }
        stage('run code'){
            steps{
                sh 'python3 python.py'
            }
        }
    }


}