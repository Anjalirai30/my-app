node{
   stage('Checkout'){
     checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Anjalirai30/my-app.git']]])

   }
   stage('Compile-Package'){
      bat 'mvn clean install'
   }
}


