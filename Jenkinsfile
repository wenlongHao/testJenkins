Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'python:3.9.2-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
