pipeline {
    agent any
    stages {
        stage("Run docker compose") {
            steps {
                sh '''
                sudo docker compose up -d --wait
                sudo docker compose ps
                '''
            }
            
        }
    }
}
