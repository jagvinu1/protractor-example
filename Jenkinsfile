pipeline{
    agent any
    stages{
        stage('Checkout'){
            steps{
                checkout([$class: 'GitSCM',
                 branches: [[name: '*/master']], 
                doGenerateSubmoduleConfigurations: false, 
                extensions: [],
                 submoduleCfg: [], 
                 userRemoteConfigs: [[url: 'https://github.com/jagvinu1/protractor-example.git']]])
            }
        }
    }
}