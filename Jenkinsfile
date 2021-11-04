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
       
