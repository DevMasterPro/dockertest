
 



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
                sh 'apk add git'
            }
        }
        stage('Test') {
            steps {
            sh  'git --version'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}









