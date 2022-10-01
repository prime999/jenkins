pipeline {
    agent any
    stages {
        stage("Run docker compose") {
            sh '''
            docker compose up -d --wait
            docker compose ps
            '''
        }
    }
}
