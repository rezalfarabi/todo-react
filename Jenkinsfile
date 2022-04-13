pipeline {
    agent any

    stages {
        stage('build app') {
            steps {
                sh 'sudo apt install update'
                sh 'sudo apt install npm'
            }
        }
        stage ('test app') {
            steps {
                sh 'npm test'
            }
        }
    }
}
