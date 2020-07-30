pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -lahtr'
                sh 'sh ./ansible.sh'
            }
        }
    }
}
