pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               sh 'mvn clean deploy'
            }
        }
        stage('Deploy') {
            steps {
               echo 'Deploy' 
            }
        }
    }
}
