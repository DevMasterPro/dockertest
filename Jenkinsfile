
 



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
        stage('Test') {
            steps {
              git --version
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}









