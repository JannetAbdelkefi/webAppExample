pipeline {    
        tools{
		maven 'maven'
		}
	agent any
    stages {
    
		
        stage("Build Application"){           
          steps {
            bat '''
            mvn clean package 
            '''
          }     
        }
         
    }
   
}
