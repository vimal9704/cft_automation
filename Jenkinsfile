pipeline {
    agent any 
    stages {
        stage('Submit stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://s3-bucket.yml --tags file://tags.json --parameter-overrides file://params.json"    
              }
             }
            }
            }
