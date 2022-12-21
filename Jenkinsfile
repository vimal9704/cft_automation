pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://s3-bucket.yml --tags file://tags.json --region 'us-east-1' --parameter file://params.json"
              }
             }
            }
            }
