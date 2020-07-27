pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -latr'
                sh 'echo $USER'
                sh 'chmod +X ansible.sh'
                sh 'sh ./ansible.sh'
            }
        }
    }
}
