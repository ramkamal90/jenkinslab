pipeline {
    agent any
    stages{
    stage ('sample1'){
        steps{
        echo 'Building...'
        bat 'python file2.py'
            }
    }
    stage ('sample2'){
        steps{
        echo 'Using maven'
        }
    }
}
}
