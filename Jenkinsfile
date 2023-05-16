pipeline {
  agent any
  stages {
    stage("build"){
      steps{
        echo "Building the application"
     }
    }
    stage("test"){
     steps{
       echo "Testing the application"
       }
      }
    stage("deploy"){
      steps{
        echo "Deploying the changes"
       }
      }
    post{
      always{
        echo "execute on success and failure"
      }
      success{
        echo "execute on success"
      }
      failure{
        echo "execute on failure"
      }
    }
   }        
