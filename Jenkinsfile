
pipeline {
    agent any

stages {
       
 stage('Clone the repository ') {
            steps {
                
             git branch: 'master', url: 'https://github.com/yankils/hello-world.git'   
                
            }
        }

stage('build with maven'){
        withMaven(maven: 'mvn') {
            sh "mvn clean package"
        }
    }
       
    
  
    }

}

