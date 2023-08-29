pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo Hello World second time!'
                sh '/usr/local/bin/aws sts get-caller-identity'
                sh '/usr/local/bin/aws ec2 describe-instances --region us-east-1'
            }
        }
    }
}