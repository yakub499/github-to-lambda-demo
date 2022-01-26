pipeline{
  agent { label 'master' }
  stages{
    stage("Build"){
      steps{
        sh "python github-to-lambda-demo/lambda_function.py"
      }    
    }
  }
}
