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
                bat 'C:\\Users\\ELCOT\\AppData\\Local\\Python\\bin\\python.exe'
                }
            }
        }
    }
