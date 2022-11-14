pipeline{
tools{
        jdk 'JAVA_HOME'
		maven 'M2_HOME'
	 }
	agent any
	
	stages{
	
	stage("checkout"){
	steps{
	'git credentialsId: 'github', url: 'https://github.com/NibeditaBishoyi/jenkinsrepo.git''
	     }
	                  }
				
    stage("compile"){
	steps{
	  sh 'mvn compile'
	     }
	                }
	     }
   }
