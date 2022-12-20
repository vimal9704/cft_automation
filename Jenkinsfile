pipeline {
    agent any 
    stages {
        stage('Submit stack') {
            steps {
            sh "aws cloudformation deploy \ --stack-name s3bucket \ --template-body file://s3-bucket.yml \ --tags file://tags.json \ --parameter-overrides file://params.json"    
              }
             }
            }
            }
