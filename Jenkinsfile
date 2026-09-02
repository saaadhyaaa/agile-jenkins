pipeline {
    agent any
    stages {
        stage('Checkout Code'){
            steps {
                git branch: 'main', url: 'https://github.com/saaadhyaaa/agile-jenkins.git'
            }

        }
        stage('Build'){
            steps{
                bat 'python sum.py'
            }
        }
    }
}