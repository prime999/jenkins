pipeline {
    agent any
    stages {
        stage("Run docker compose") {
            sh 'docker compose up -d --wait'
            sh 'docker compose ps'
        }
    }
}