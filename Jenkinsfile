pipeline {
    agent any
   tools{
       nodejs 'NodeJS'
   }
    stages {
        stage('Build') { 
            
            steps {
                sh 'node --version'
                sh '''
                    npm install -g @angular/cli
                    
                '''
            }
        }
       
    }
}