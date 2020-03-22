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
                sh label: '', script: 'sudo npm install'
                sh label: '', script: 'sudo npm install -g protractor'
                sh label: '', script: 'webdriver-manager update'
                sh label: '', script: 'webdriver-manager start'
                sh label: '', script: 'protractor conf.js'
                }
        }
    }
}