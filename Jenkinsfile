pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'javac Calculator.java'
            }
        }

        stage('Execute') {
            steps {
                sh 'java Calculator'
            }
        }
    }
}
