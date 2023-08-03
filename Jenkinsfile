pipeline {
    agent any



    stages {
        stage('test') {
           
            steps {
               sh "echo deploy to production"
               def common = load "common.groovy"

                common.mycommoncode()
            }
            
        }
        
        stage('Deploy to UAT') {
          
            steps {
               sh "echo deploy to uat"
            }
            
        }
    }
}