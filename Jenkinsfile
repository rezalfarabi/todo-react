pipeline {
    agent any
    
    tools {nodejs "node"}

    stages {
        stage('build app') {
            steps {
                sh 'apt install update'
                sh 'apt install npm'
            }
        }
        stage ('test app') {
            steps {
                sh 'npm test'
            }
        }
    }
}
