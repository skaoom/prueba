pipeline {
    agent any
    stages {
        stage('Build'){
            steps{
                sh "docker build -t skaoom/pokedex-flask:${env.BUILD_NUMBER} ."
            }
        }
    }
}
