node{
   stage('SCM Checkout'){
     git 'https://github.com/git212/bharat22/Jenkinsfile'
   }
   stage('compile-package'){
      // Get maven home path
      def mvnHome = tool name: 'maven3', type: 'maven'
      sh "${mvnHome}/bin/mvn package"
   }
}
