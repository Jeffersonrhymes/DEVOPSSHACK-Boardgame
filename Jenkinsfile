pipeline {
    agent any
    tools {
        maven 'maven3'
    }

        
         stage('Compile') {
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
