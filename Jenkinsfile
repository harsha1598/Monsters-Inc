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
                echo "build step"
            }
        }
        stage('deploy') {
            steps {
                echo "deployed"
            }
        }
        stage('Complete') {
            steps {
                echo "SUCCESS"
            }
        }
    }
}
