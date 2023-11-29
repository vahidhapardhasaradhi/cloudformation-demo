pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://vahidhas3.json --region 'us-east-2'"
              }
             }
            }
            }
