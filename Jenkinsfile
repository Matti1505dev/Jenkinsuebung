pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Klont das GitHub-Repository
                git 'https://github.com/Matti1505dev/Jenkinsuebung.git'
            }
        }
        stage('Build') {
            steps {
                // Führt einen simplen Shell-Befehl aus
                sh 'echo "Building project"'
            }
        }
        stage('Deploy') {
            steps {
                // Simuliert ein Deployment
                sh 'echo "Deploying application"'
            }
        }
    }
}
