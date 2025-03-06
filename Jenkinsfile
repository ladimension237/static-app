pipeline {
    agent any 
    stages{
        stage ('CodeScan'){
           steps {
                sh 'touch file.txt'
                sh 'echo " it works">file.txt'
                sh 'cat file.txt'
           } 
        }
    }
}