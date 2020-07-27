pipeline {
    agent any
    stages {
        stage('Terraform_Installation') {
            steps {
                sh 'pwd'
                sh 'ls -ltr'
                sh 'echo $USER'
                sh 'sudo chown -R root:root ansible.sh'
                sh 'sudo chmod 777 ansible.sh'
                sh 'sh ansible.sh'
            }
        }
    }
}
