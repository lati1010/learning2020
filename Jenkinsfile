pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'wget https://releases.hashicorp.com/terraform/0.12.24/terraform_0.12.24_linux_amd64.zip'
                sh 'apt-get install zip -y'
                sh 'unzip terraform*.zip'
                sh 'mv terraform /usr/local/bin'
                sh 'terraform version'
                sh 'sudo apt-get install zip -y'
                sh 'sudo unzip terraform*.zip'
                sh 'sudo mv terraform /usr/local/bin'
                sh 'sudo terraform version'
            }
        }
    }
