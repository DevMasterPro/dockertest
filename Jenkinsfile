pipeline {  
    agent { 
        dockerfile {
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
 
