
pipeline {
  agent any
    
  stages {
     
    stage('Build') {
      steps {
        sh "/usr/bin/npm install"
      }
    }  
    
            
    stage('Test') {
      steps {
        sh 'node test'
      }
    }
  }
}
