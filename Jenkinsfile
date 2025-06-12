pipeline { 
    agent any 
    stages { 
        stage('Compilation') { 
            steps { 
                bat 'javac HelloWorld.java' 
            } 
        } 
        stage('Ex‚cution') { 
            steps { 
                bat 'java HelloWorld' 
            } 
        } 
    } 
} 
