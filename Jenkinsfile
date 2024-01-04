
pipeline {
    agent any
      tools{
        maven 'Maven3.9.6'
    }

stages {
       
 stage('Clone the repository ') {
            steps {
                
             git branch: 'master', url: 'https://github.com/yankils/hello-world.git'   
                
            }
        }

 stage("Build the code") {
           
           steps{
               sh 'mvn clean install'
           }
       }
       
    
  
    }

}

