@Library('my-shared-library') _
 pipeline {
  agent any

   stages {
    stage("POLL SCM"){
      steps {
        script{ 
            gitCheckout(
                branch: "main",
                url: ""
            )
     }
    }
   }
  }  
 }
}
