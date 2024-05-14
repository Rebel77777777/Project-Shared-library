@Library('my-shared-library') _
 pipeline {
  agent any

   stages {
    stage("POLL SCM"){
      steps {
        script{ 
            gitCheckout(
                branch: "main",
                url: "https://github.com/vikash-kumar01/mrdevops_java_app.git"
            )
     }
    }
   }
  }  
 }
}
