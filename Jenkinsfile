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
          echo "its testing"
          bat "dir"
           } 
      }
   stage('deploy'){
      steps{
          echo "its deploying"
           } 
      }
  }
}
