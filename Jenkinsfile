pipeline {
    
    agent any

    stages
    {
         stage('Build')
         {
            steps
            {
                echo 'Building Now'
            }
        }
         stage('Test')
         {
            steps
            {
                echo 'Testing Now'
            }
        }
         stage('Deploy')
         {
            steps
            {
                echo 'Deploying Now'
            }
        }
    }
    post {
        always{
            
            emailext body: 'its from jenkins pipeline.', subject: 'pipeline status', to: 'mahnoorshafique45@gmail.com'
        }
    }
    
}
