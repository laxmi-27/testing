
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Run App') {
            steps {
                bat '"C:\\Users\\admin\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" app.py'
            }
        }
    }
}
