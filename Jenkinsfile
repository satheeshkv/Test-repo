pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                /bin/sh 'ps -ef | grep httpd'
                /bin/sh 'docker image ls | grep httpd'
            }
        }
    }
}
