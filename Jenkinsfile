pipeline {
    agent any
    tools { 
        maven 'Maven 3.3.9' 
        jdk 'jdk8' 
    }
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
