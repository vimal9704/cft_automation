pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --template-body file://ec2.yml --stack-name single-instance --parameters ParameterKey=InstanceType,ParameterValue=t2.micro --region 'ap-south-1'"
              }
             }
            }
            }
