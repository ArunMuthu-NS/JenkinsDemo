pipeline {
    agent {
        image 'maven:3-alphine'
        args '-v /root/.m2:/root/.m2'
    }
    stages {
        stage('Build') {
            steps{
                sh  'mvn clean package'
            }
        }
    }
}