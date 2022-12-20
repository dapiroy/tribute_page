pipeline {
    
    agent any 
    
    stages {
        
        stage('Git Checkout') {
            
            steps {
                
                script {
                    
                    git branch: 'master', url: 'https://github.com/dapiroy/tribute_page.git'
                }
            }
        }
