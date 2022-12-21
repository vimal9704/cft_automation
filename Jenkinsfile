pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2 --template-body file://ec2.yaml --parameters [{
    "ParameterKey": "VpcId",
    "ParameterValue": "vpc-08d6de661501d6a09"
  },
  {
    "ParameterKey": "SubnetId",
    "ParameterValue": "subnet-0ae420d5cdcfb21bd"
  },
  {
    "ParameterKey": "InstanceName",
    "ParameterValue": "ec2-instance"
  },
  {
    "ParameterKey": "SshCidrAllow",
    "ParameterValue": "0.0.0.0/0"
  },
  {
    "ParameterKey": "InstanceType",
    "ParameterValue": "t2.large"
  },
  {
    "ParameterKey": "KeyName",
    "ParameterValue": "key-name"
  }] --region 'ap-south-1'"
              }
             }
            }
            }
