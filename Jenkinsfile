pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://s3-bucket.yml --region 'ap-south-1'"
              }
             }
            }
            }
