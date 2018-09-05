pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'echo start'
                sh 'mvn clean build' 
                sh 'echo stop'
            }
        }
    }
}
