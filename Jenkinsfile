git branch: 'main', credentialsId: 'e35533e2-159a-4754-a294-a1e8b67219ec', url: 'https://github.com/x-neon-nexus-o/TEIT_26.git'
pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
               git branch: 'main', credentialsId: 'e35533e2-159a-4754-a294-a1e8b67219ec', url: 'https://github.com/x-neon-nexus-o/TEIT_26.git'
            }
        }
        stage('Compile') {
            steps {
                bat 'javac HelloWorld.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java HelloWorld'
            }
        }
    }
}
