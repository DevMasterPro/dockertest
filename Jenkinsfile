pipeline {
    agent { label "testa" 
          dockerfile true }
    stages {
        agent {
        stage('Test') {
            steps {
             sh 'git --version'
            }
        }
        }
    }
}
