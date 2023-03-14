/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stage('clean up') {
            steps {
                deleteDir()
            }
        }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
        stage('Complete') {
            steps {
                echo "SUCCESS"
            }
        }
    }
}
