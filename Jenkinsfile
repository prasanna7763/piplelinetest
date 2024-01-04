
pipeline {
    agent any

stages {
       
 stage('Clone the repository ') {
            steps {
                
             git branch: 'master', url: 'https://github.com/yankils/hello-world.git'   
                
            }
        }

 stage("Build the code") {
           
           steps{
               sh 'mvn clean package'
           }
       }
       
    
  
    }

}

