pipeline {
    agent any
    stages {
        stage('git pull'){
            steps{
                git branch: 'main', url: 'https://github.com/ashishdubey123/student1.git'
            }
        }
        stage('mvn clean'){
            steps{
                sh 'mvn clean'
            }
        }
        
    }
}