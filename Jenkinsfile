pipeline {  
    agent { 
        dockerfile {
            label 'docker'
        }
    }
    stages {
        stage('Build') {
            steps {
              sh 'node --version'
                sh 'svn --version'
                sh 'apt-get install git -y'
                
            }
        }
    }
    
    
        stages {
        stage('Test') {
            steps {
              sh 'node --version'
                sh 'svn --version'
                sh 'apt-get install git -y'
                
            }
        }
    }
    
    
    
}
 


