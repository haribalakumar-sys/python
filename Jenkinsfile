pipeline{
    agent any
    {
        stages{
            stage('Checkout')
            {
                steps{
               checkout scm
                }
            }
            stage('run')
            {
                steps{
                bat 'python fac1.py'
                }
            }
        }
    }
}