pipeline {
    agent {
    // Equivalent to "docker build -f Dockerfile.build --build-arg version=1.0.2 ./build/
    dockerfile {
        filename 'Dockerfile.httpd'
        //dir 'build'
        label 'docker-httpd-lable'
        additionalBuildArgs  '--build-arg version=1.0.2' '-t httpd-docker-image'
        args '-v /tmp:/tmp'
    }
 }

}
