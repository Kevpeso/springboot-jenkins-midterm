pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/Kevpeso/springboot-jenkins-midterm.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }

    }
}
