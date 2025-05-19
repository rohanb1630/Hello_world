pipeline {
    agent any
    
    tools {
        jdk 'jdk 17.0.15' 
    }
    
    stages {
        stage('Build') {
            steps {
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
