/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('loadrepo') {
            steps {
                bat 'vrunner loadrepo'
            }
        }
    }
}