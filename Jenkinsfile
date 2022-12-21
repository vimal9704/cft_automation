pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2 --template-body file://ec2.yaml --parameters file://ec2-parameters.json --region 'ap-south-1'"
              }
             }
            }
            }
