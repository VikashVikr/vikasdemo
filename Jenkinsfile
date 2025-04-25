pipeline {
    agent any
    stages {
        stage('dev') {
            steps {
                sh  "/tmp/staging.sh"
            }
        }
        stage('staging') {
            steps {
                sh  "/tmp/staging.sh"
            }
        }
        stage('prod') {
            steps {
                 sh  "/tmp/prod.sh"
            }
        }
    }
}
