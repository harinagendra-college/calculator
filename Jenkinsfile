
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code Checkout Successful'
            }
        }

        stage('Build') {
            steps {
                bat 'javac Calculator.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java Calculator'
            }
        }
    }
}
