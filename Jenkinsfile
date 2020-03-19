node{
   stage('SCM Checkout'){
     git 'https://github.com/git212/bharat22.git'
   }
   stage('compile-package'){
      // Get maven home path
      def mvnHOME = tool name: 'maven3', type: 'maven'
      sh "${mvnHome}/bin/mnn package"
   }
}
