pipeline {
    agent any

    stages {
        stage('build app') {
            steps {
                sh 'sudo npm install'
            }
        }
        stage ('test app') {
            steps {
                sh 'npm test'
            }
        }
    }
}
