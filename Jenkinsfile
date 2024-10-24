pipeline {
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                scrpit {
                    sh '''
                    docker build -t balaji:1.0
                    '''
                }
            }
        }
    }
}
