pipeline {
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage(label 'docker') {
            steps {
                sh 'python --version'
            }
        }
    }
}
