@Library('my-shared-library') _
 pipeline {
  agent any

   stages {
    stage("POLL SCM"){
      steps {
        script{ 
            gitCheckout(
                branch: "main",
                url: "https://github.com/Rebel77777777/Project-Shared-library.git"
            )
     }
    }
   }
  
   stage('Unit Test maven'){

            steps{
               script{

                     mvnTest()
               }
       }  
     }
    }
   }

