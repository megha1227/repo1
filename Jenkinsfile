pipeline{
  agent any
  stages{  
    stage('build'){
      steps{
          echo "its building"
          bat "dir"
           } 
      }
    parallel{
    stage('test'){
      steps{
         bat "for /l %%x in (1, 1, 100000000) do echo %%x" 
         echo "its testing"
          bat "dir"
           } 
      }
   stage('deploy'){
      steps{
        bat "for /l %%x in (1, 1, 100000000) do echo %%x"  
        echo "its deploying"
           } 
      }
    }
    }
}
