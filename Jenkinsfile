pipeline {
    agent any 
    stages {
        stage('clean') { 
            steps {
                sh "mvn clean" 
            }
        }
        stage('compile') { 
            steps {
                sh "mvn complie" 
            }
        }
        stage('test') { 
            steps {
                sh "mvn test" 
            }
        }
        stage('package') { 
            steps {
                sh "mvn package"
            }
        }
    }
}
