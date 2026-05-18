pipeline {
    agent any

    stages {
        stage ("check_out") {
            steps {
                git branch: 'main', 
                credentialsId: 'jnekins_ci', 
                url: 'https://github.com/pabhishek1994-pixel/ca_demo_express.git'
            }
        }
        stage ("dw_jb") {
            steps {
                sh '''
                pwd
                ls -ltr
                '''
            }
        }
    }
}
