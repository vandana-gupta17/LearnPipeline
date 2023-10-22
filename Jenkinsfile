node{
  stage('SCM Checkout'){
    git 'https://github.com/vandana-gupta17/LearnPipeline'
  }
  stage('compile-package'){
    sh 'mvn package'
  }
}
