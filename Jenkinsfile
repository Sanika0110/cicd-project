pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
             steps {
        sh 'cp /var/lib/jenkins/workspace/cicd-project/index.html /var/www/html/'
    }
}
