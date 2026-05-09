pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/pabhishek1994-pixel/jenkins_repo.git'
                    credentialsId: 'github_connect'
            }
        }

        stage('Build') {
            steps {
                sh 'ls -lrt'
            }
        }
    }
}
