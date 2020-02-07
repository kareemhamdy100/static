pipeline {
    agent any
    stages {
        stage('Upload to AWS.') {
            steps {
              withAWS(region:'us-est-1', credentials: 'aws-static' ) {
                  s3Upload(file:'index.html', bucket:'kareem-jenkins', path:'/')
                }
            }
        }
    }
}