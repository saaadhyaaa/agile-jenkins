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
                sh ''' printf "10\\n20\\n" | python sum.py '''
            }
        }
    }
}