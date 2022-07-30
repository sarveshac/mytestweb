node{
   stage('SCM Checkout'){
     git 'https://github.com/sarveshac/mytestweb'
   }
   stage('Compile-Package'){
      // Get maven home path
       def mvnHome = tool name: 'apache-maven-3.5.3', type: 'maven'
	  sh "${mvnHome}/bin/mvn package"     
   }
    
 }
