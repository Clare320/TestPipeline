Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker 'node:12.6.0' }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
                sh 'echo "Hello World"'
            }
        }
    }
}