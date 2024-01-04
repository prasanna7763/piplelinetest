
pipeline {
    agent any
        tools{
        maven 'Maven 3.6.3'
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

