node{
   stage('SCM Checkout'){
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-Package'){
      // Get maven home path
    bat '''def mvnHome =  tool name: \'MAVEN\', type: \'maven\'  
      bat \'{mvnHome}/mvn package\''''
   }
}


