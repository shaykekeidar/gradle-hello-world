pipeline {
    agent any
    stages{
        stage('checkout'){
            steps{
            
            checkout scm

            }
        }
        stage('build'){
            agent  { label 'master' }
            steps{
            }
        }
    }
}
    
