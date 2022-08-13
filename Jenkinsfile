pipeline {
    agent {
label{
		label "master"
		customWorkspace "/mnt/vishwesh"
}
}

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

