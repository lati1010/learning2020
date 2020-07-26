pipeline {
    agent any
    stages {
        stage('test2') {
            steps {
                sh 'echo "Hello World"'
                sh 'systemctl status jenkins'
                sh 'df -h'
                sh '''
                    echo "Multiline shell steps works too"
