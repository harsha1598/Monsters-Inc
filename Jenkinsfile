/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    
    stages {
        stage('clean up') {
            steps {
                deleteDir()
            }
        }
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
