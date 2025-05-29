pipeline {
    agent any

    tools {
        maven 'Maven'   // Replace with your configured Maven name in Jenkins
        jdk 'JDK'          // Replace with your JDK name in Jenkins
    }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Nischay2004/MyGuavaApp.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}

