pipeline{
  agent none
  stages{
    stage("Build"){
      steps{
        step{
          sh "python lambda_function.py"
        }
      }    
    }
  }
}
