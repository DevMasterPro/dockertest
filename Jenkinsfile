pipeline {  
    agent { 
        dockerfile {
            label 'docker'
        }
    }
    stages {
        stage('Test') {
            steps {
              sh 'node --version'
                sh 'svn --version'
            }
        }
    }
}
 


