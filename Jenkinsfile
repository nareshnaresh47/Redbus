pipeline {
    agent any
	
	  tools
    {

       maven "ANt"
       maven "mavennnnnn"

    }
 stages {
      stage('checkout') {
           steps {
             
                git branch: 'master', url: 'https://github.com/nareshnaresh47/Redbus.git'
             
          }
        }
	 stage('Execute Maven Build') {
           steps {
		sh '''
		mvn package
		pwd
		ls -lart
		touch "hello.txt"
		
		
		'''
          }
        }
        

 
     
  
    }
	}
