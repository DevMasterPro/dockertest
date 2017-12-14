pipeline {
    agent { label "testa" }
    stages {
        agent { dockerfile true }
        stage('Test') {
            steps {
             sh 'git --version'
            }
        }
    }
}
