pipeline{
  agent { label 'master' }
  stages{
    stage("Build"){
      steps{
        sh "python3 lambda_function.py"
      }    
    }
  }
}
