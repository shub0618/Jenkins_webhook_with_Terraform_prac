pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
                git branch: 'main', url: 'https://github.com/shub0618/jenkins_webhook-prac.git'
            }
        }
        stage('init') {
            steps {
                sh 'terraform init'
            }
        }
    }
}
