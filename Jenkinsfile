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
         bat "ping localhost -n 30  >nul && :: will wait 3 seconds before going next command (it will not display)" 
         echo "its testing"
          bat "dir"
           } 
      }
   stage('deploy'){
      steps{
        bat "ping localhost -n 30 >nul && :: will wait 3 seconds before going next command (it will not display)"  
        echo "its deploying"
           } 
      }
  }
}
