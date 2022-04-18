
pipeline {
    agent any
   
               
       stages {
            stage('SCM checkout') {
                  steps {
                        git url: 'https://github.com/testproject654/Sentrifugo.git'
                        }
             }
             
            
           
           stage('test') {
                  steps {
                          sh 'whoami'
                          sh 'ls -a'
                         
                        }
              }
           
             
       }
}
