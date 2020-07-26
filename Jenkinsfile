pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'wget https://releases.hashicorp.com/terraform/0.12.24/terraform_0.12.24_linux_amd64.zip'
                sh 'apt-get install zip'
                sh 'sudo unzip terraform*.zip'
                sh 'sudo mv terraform /usr/local/bin'
                sh 'sudo terraform version'
            }
        }
    }
}
