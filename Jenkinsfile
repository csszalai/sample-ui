
pipeline {
    agent {
         { image 'node:7-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
                sh 'ls -lah'
                echo "Removed Lightweight checkout option from pipeline job git SCM settings."
            }
        }
    }
}
