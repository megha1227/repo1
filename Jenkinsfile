pipeline{
  agent any
  stages{  
    stage('build'){
      steps{
          echo "its building"
           } 
      }
   stage('test'){
      steps{
         bat "timeout 30" 
         echo "its testing"
          bat "dir"
           } 
      }
   stage('deploy'){
      steps{
        bat "timeout 30"  
        echo "its deploying"
           } 
      }
  }
}
