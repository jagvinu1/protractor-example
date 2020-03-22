pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
               git 'https://github.com/jagvinu1/protractor-example'
            }
        }
        stage('testing') {
            steps {
                sh 'node -v'
                }
        }
    }
}