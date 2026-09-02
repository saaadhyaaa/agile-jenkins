pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git url: 'https://github.com/saaadhyaaa/agile-jenkins.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                /* 
                   Using (echo num1 && echo num2) sends '5' as the first input 
                   and '10' as the second input into the python script.
                */
                bat '(echo 5 && echo 10) | python sum.py'
            }
        }
    }
}
