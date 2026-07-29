pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Compile Java') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }

        stage('Run Java') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}
