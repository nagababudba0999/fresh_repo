pipeline {
    agent any 
    stages {
        
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

