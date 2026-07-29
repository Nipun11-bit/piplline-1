pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
               git branch: 'main', url: 'https://github.com/Nipun11-bit/piplline-1.git'
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
