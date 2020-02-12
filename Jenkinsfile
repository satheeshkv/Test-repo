pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                 sh 'ps -ef | grep httpd'
                
            }
        }
    }
}
