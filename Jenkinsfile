pipeline {
    agent any
    tools {
        maven 'maven3'
    }

        
         stage('Compile') {
            steps {
                sh 'mvn compile'
            }
        }


         stage('Build') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
