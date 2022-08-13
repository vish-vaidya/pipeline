pipeline {
    agent any

    stages {
        stage('coping') {
            steps {
                sh 'cp -r index.html /var/www/html'
            }
        } 
    stages {
        stage('restart') {
            steps {
                sh 'service httpd restart'
            }
        }

    }
}

