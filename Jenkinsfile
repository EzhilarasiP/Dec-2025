pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
           
                git branch: 'main', url: 'https://github.com/EzhilarasiP/Dec-2025.git'
            }
        }
        stage('Run Python Script') {
            steps {
           
                bat 'python s.py'

               
            }
        }
    }
}

