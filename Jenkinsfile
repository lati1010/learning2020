pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -lhatr'
                sh 'sudo cp /var/lib/jenkins/workspace/learning/ansible.sh /home/ubuntu/'
                sh 'sh ./ansible.sh'
            }
        }
    }
}
