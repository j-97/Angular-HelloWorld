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
                    pwd
                    npm install
                    ng serve --host 0.0.0.0
                '''
            }
        }
       
    }
}