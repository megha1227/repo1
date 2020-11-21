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
         SLEEP 10 
         echo "its testing"
          bat "dir"
           } 
      }
   stage('deploy'){
      steps{
        SLEEP 10  
        echo "its deploying"
           } 
      }
  }
}
