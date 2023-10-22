node{
  stage('SCM Checkout'){
    git 'https://github.com/vandana-gupta17/LearnPipeline'
  }
  stage('compile-package'){
      def mvnHome = tool name: 'M3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
