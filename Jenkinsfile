pipeline {

    agent any


    stages {
       stage ('Pull') {
            steps {
               script{
                   checkou([$class: 'GitSCM', branches:[[name: '*/master']],
                      userReoteconfigs: [[
                           credentialsId: "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", 
                           url: "https://github.com/mahmoudbenayed16/CD-Project.git"]]])
  
  
               
               }
            }
       }
    
    }
    }
       
