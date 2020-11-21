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
         bat "SLEEP 10" 
         echo "its testing"
          bat "dir"
           } 
      }
   stage('deploy'){
      steps{
        bat "SLEEP 10"  
        echo "its deploying"
           } 
      }
  }
}
