pipeline {
    agent  any
          
    stages {
        stage('build1'){
            steps{
                sh ' hostname'
            }
        }
        stage('build2') {
            steps {
                sh 'pwd bobo/roma.txt'
                sh ' ls -a'
                sh 'echo "hugry" >> bobo/roma.txt '
                retry (3) {
                    sh ' cat bobo/roma.txt}
                sh 'pwd'
                sh ' ansible-playbook ~/src/ansible_new/fdo-2268/ansible/lfp-stg/user.yml -CD  -i hosts.txt '
            }
        }
       
             
                    
            
        }
    }

