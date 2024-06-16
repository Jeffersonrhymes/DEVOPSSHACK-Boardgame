pipeline {
    agent any
    tools {
        maven 'maven3'
    }

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Jeffersonrhymes/DEVOPSSHACK-Boardgame.git'
            }
        }
        
         stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
