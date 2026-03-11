pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/hyeongpark12345/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh './mvnw clean package'
            }
        }

    }


