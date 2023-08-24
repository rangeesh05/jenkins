pipeline{
  agent any

  trigger{
    githubPush()
  }

  stages{
    stage('checkout'){
      steps{

        checkout scm
      }
    }
  }
}
