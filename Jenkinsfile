pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                sh 'ps -ef | grep httpd'
                sh 'docker image ls | grep httpd'
            }
        }
    }
}
