pipeline {
    agent any
	
	  tools
    {
<<<<<<< HEAD
       maven "ANt"
=======
       maven "mavennnnnn"
>>>>>>> f032c2e5b8e8e7ef3a72bee7304cd54c5045db67
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
