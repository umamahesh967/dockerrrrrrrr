pipeline {
    agent any
    stages {
        stage('Deploy') {
            steps {
                sh 'docker-compose -f docker-compose.yml up -dc'
            }
        }
    }
}
