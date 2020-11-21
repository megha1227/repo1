pipeline{
  agent any
  stages{  
    stage('build'){
      steps{
          echo "its building"
          bat "dir"
           } 
      }
   stage('test'){
      steps{
         bat "timeout 30 >nul" 
         echo "its testing"
          bat "dir"
           } 
      }
   stage('deploy'){
      steps{
        bat "timeout 30 >nul"  
        echo "its deploying"
           } 
      }
  }
}
