pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                 'ps -ef | grep httpd'
                 'docker image ls | grep httpd'
            }
        }
    }
}
