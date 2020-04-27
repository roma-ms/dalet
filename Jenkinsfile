pipeline {
    agent { docker 
           { image 'ubuntu:18.04' } 
          }
    stages {
        stage('build1'){
            steps{
                sh ' hostname'
            }
        }
        stage('build2') {
            steps {
                sh 'touch bobo/roma.txt'
                sh ' ls -a'
                sh 'hostname'
            }
        }
       
             
                    
            
        }
    }

