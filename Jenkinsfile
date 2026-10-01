pipeline{
    agent any
    
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
                bat 'C:\\Users\\ELCOT\\python\\python.exe fac1.py'
                }
            }
        }
    }
