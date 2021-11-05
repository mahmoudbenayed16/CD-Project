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
       
