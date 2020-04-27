pipeline {
    agent { docker 
           { image 'ubuntu:18.04' } 
          }
    stages {
        stage('build1') {
            steps{ sh 'lsb-release'
                 }
        }
        stage('build2') {
            steps {
                sh 'mkdir bobo'
                sh 'touch roma.txt'
            }
        }
       
             
                    
            
        }
    }

