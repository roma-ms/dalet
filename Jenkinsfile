pipeline {
    agent { docker 
           { image 'ansible:2.9.2' } }
    stages {
        stage('build') {
            steps {
                sh 'ansible --version'
            }
        }
    }
}
