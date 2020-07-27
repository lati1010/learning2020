pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'wget https://releases.hashicorp.com/terraform/0.12.24/terraform_0.12.24_linux_amd64.zip'
                sh 'pwd'
                sh 'chown -R 1000:1000 ansible.sh'
                sh 'sudo su'
                sh 'sh ansible.sh'
            }
        }
    }
}
