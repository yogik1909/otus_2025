/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('loadrepo') {
            steps {
                bat 'chcp 65001\n vrunner loadrepo'
            }
        }
        stage('syntax-check') {
            steps {
                bat 'chcp 65001\n vrunner syntax-check --mode -HandlersExistence'
            }
        }
    }
}