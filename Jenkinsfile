pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo Hello World second time!'
                sh '/usr/local/bin/aws configure set AWS_ACCESS_KEY_ID AKIAZ2N4AAIJ2PJAONBO'
                sh '/usr/local/bin/aws configure set AWS_SECRET_ACCESS_KEY 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'
                sh '/usr/local/bin/aws configure set AWS_DEFAULT_REGION us-east-1'
                sh '/usr/local/bin/aws sts get-caller-identity'
                sh '/usr/local/bin/aws s3 ls'
            }
        }
    }
}