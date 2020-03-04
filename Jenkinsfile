pipeline {
    agent { docker { image 'quickcorp/qcobjects:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'qcobjects --version'
            }
        }
    }
}
