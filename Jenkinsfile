pipeline{
  agent { label 'master' }
  stages{
    stage("Build"){
      steps{
        sh "python lambda_function.py"
      }    
    }
  }
}
