pipeline {

    agent any


    stages {
       stage ('Pull') {
            steps {
               script{
                   checkout([$class: 'GitSCM', branches:[[name: '*/master']],
                      userReoteconfigs: [[
                           credentialsId: "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", 
                           url: "https://github.com/mahmoudbenayed16/CD-Project.git"]]])
  
  
               
               }
            }
       }
    
    }
    }
       
