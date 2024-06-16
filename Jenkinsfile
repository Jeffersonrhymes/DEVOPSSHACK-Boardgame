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

         stage('Compile') {
            steps {
                sh 'mvn test'
            }
        }
stage('Test') {
              steps {
                  sh 'mvn test'
              }
          }
        

         stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
