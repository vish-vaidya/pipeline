pipeline {
    agent any
stages {
        stage ('make') {
            steps {
                sh 'mkdir vish'
            }
        } 
        stage('restart') {
            steps {
                sh 'service httpd restart'
            }
        }

    }
}

