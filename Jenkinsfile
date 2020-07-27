pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -latr'
                sh 'echo $USER'
                sh 'chmod +x ansible.sh'
                sh 'sh ./ansible.sh'
            }
        }
    }
}
