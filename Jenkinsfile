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
                sh ' rm bobo/roma.txt'
                sh ' touch bobo/roma.txt'
                sh 'echo "hugry" >> bobo/roma.txt '
                retry (3) {
                    sh ' cat bobo/roma.txt'}
                sh 'pwd'
                sh ' ansible-playbook ~/src/ansible_new/fdo-2268/ansible/lfp-stg/users.yml -CD  -i hosts.txt '
            }
        }
       
             
                    
            
        }
    }

