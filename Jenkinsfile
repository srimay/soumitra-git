pipeline {
    agent any
    
    stages {
        stage('Execute Ansible Scripts') {
            steps {
                sh 'sudo ansible-playbook /home/srimay/Documents/ansible/server/check_server_details.yaml'
            }
        }
        stage('Code Executed') {
            steps {
                echo 'Code Executed Sucessfully'
            }
        }
        
    }
}
