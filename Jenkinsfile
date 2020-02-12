pipeline {
    agent {   dockerfile {
        filename 'Dockerfile.httpd'
        label 'docker-httpd-lable'
        additionalBuildArgs  '--build-arg version=1.0.2' '-t httpd-docker-image'
        args '-v /tmp:/tmp'
    }
 }
}
