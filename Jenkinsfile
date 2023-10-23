node{
  stage('SCM Checkout'){
    git 'https://github.com/vandana-gupta17/LearnPipeline'
  }
  stage('Compile-Package'){
       tool name: 'M3', type: 'maven'
  }
}
