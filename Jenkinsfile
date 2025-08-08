pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                bat '"c:\\Users\\dell\\AppData\\Local\\Programs\\Python\\Python313\\python.ex" /c python --version'
            }
        }
        stage('hello'){
            steps{
                bat '"c:\\Users\\dell\\AppData\\Local\\Programs\\Python\\Python313\\python.ex" /c python demoxy.py'

            }
        }
    }
}