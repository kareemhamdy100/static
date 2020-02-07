pipeline {
    agent any
    stages {
        stage('Upload to AWS.') {
            steps {
              withAWS(region:'us-est-1', credentials: 'AKIA4R2JFG5DBSONU2FU' ) {
                  s3Upload(file:'index.html', bucket:'kareem-jenkins', path:'/')
                }
            }
        }
    }
}