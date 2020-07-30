pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -lhatr'
                sh 'sh ./ansible.sh'
            }
        }
    }
}
