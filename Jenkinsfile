pipeline {
    agent any 
    stages {
        stage(''checkout from script){
            steps{
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/nagababudba0999/fresh_repo.git']]])
            }           
        }
        stage('Build') { 
            steps {
                echo "Build Step"
            }
        }
        stage('Test') { 
            steps {
                echo "Testing Step"
                sh "pwd"
            }
        }
        stage('Deploy') { 
            steps {
                echo "Deployment Step"
                sh "ls"
            }
        }
    }
}

