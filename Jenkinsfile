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
                bat 'C://Users//ELCOT//AppData//Local//Programs//Python//Python314//python.exe fac1.py'
                }
            }
        }
    }
