pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                bat '"C:\\Users\\dell\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" /C python --version'
            }
        }
        stage('hello'){
            steps{
                bat '"C:\\Users\\dell\\AppData\\Local\\Programs\\Python\\Python313\\python.exe" /C python demoxy.py'

            }
        }
    }
}
