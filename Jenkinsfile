pipeline {
    agent { docker { image 'node:11.6' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
