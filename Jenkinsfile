pipeline {
 agent any

  stages {
   stage("POLL SCM"){
     steps {
       script{ 
          gitcheckout {
            branch: "main"
            url : ""
          }
    }
   }
  }  
 }
}
