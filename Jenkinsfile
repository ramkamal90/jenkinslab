pipeline {
    agent any
    stages{
    stage ('sample1'){
        steps{
        echo 'Building...'
        sh 'python file2.py'
            }
    }
    stage ('sample2'){
        steps{
        echo 'Using maven'
        }
    }
}
}
