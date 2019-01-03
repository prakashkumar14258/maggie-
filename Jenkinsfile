pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                sh 'git clone https://github.com/prakashkumar14258/maggie-.git '
                sh 'docker build -t prakashkumar12345:${BUILD_NUMBER} -f Dockerfile .'
                sh 'docker push prakashkumar12345:${BUILD_NUMBER}'
                sh 'ls'
                sh 'rm -rf maggie-'
              
                 
            }
        }
    }
}