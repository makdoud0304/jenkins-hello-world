pipeline {
    agent any
    tools {
        jdk 'jdk-22'
    }
    stages {
        stage('Compilation') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }
        stage('Ex�cution') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}

