pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "hello World"'
                sh '''
                    echo "Multliline shell steps works too"
                    ls -lah
                    '''
            }
        }
    }
}