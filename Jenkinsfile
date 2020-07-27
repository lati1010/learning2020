pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -latr'
                sh 'echo $USER'
                sh 'sudo chmod 777 ansible.sh'
                sh 'sudo chown -R root:root ansible.sh'
                sh 'sh ansible.sh'
            }
        }
    }
}
