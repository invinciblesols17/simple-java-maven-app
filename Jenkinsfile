pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'echo start'
                sh 'mvn clean package' 
                sh 'echo stop'
            }
        }
    }
}
