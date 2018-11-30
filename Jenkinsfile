node{
   stage('SCM Checkout'){
     git 'https://github.com/javahometech/my-app'
   }
   stage('Compile-Package'){
      // Get maven home path
      def mvnHome =  'D://Anjali//DevOps/apache-maven-3.6.0/bin'   
      bat '${mvnHome}/mvn package'
   }
}


