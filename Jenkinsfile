
pipeline {
    agent { label "docker-jenkins-jnlp-slave" }

    stages {
        stage('Test') {
            steps {
                sleep 10
                sh 'ls -lah'
                sh 'git log -3'
                sh "cat Jenkinsfile"
            }
        }
    }
}
