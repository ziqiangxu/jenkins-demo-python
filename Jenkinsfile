pipeline {
    agent { docker 'python:3.7.1' }
    stages {
        stage('build') {
            steps {
                sh 'python --version; echo this is the greeting text!; echo test2'
            }
        }
    }
}

