pipeline {  
    agent { 
        dockerfile true {
            lable 'docker'
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
 
