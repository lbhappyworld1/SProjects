pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('Test') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
