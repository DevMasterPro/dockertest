pipeline {  
    agent { 
        dockerfile true 
        node {
            label 'docker'
        }
    }
    stages {
        stage('Test') {
            steps {
             sh 'git --version'
            }
        }
    }
}
 
