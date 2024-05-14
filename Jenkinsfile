pipeline {
 agent any

  stages {
   stage("POLL SCM"){
     steps {
       script{ 
          gitcheckout {
            branch: "main"
            url : "https://github.com/Rebel77777777/Project-Shared-library.git"
          }
    }
   }
  }  
 }
}
