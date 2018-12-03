node{
   stage('Checkout'){
     checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Anjalirai30/my-app.git']]])

   }
   stage('Compile-Package'){
      // Get maven home path
      mvn clean install
   }
}


