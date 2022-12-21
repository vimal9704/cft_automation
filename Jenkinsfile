pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --template-body file://ec2.yml --stack-name single-instance --region 'ap-south-1'"
              }
             }
            }
            }
