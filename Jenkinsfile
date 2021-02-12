pipeline {
  agent any
  stages {
    stage(build) {
      steps {
        "echo building apps"
        }
    }
    stage(test) {
      steps {
        sh "echo testing apps"
        }
    }
    stage(deploy) {
      steps {
        sh "echo deploying apps"
        }
    }    
  }
  post {
    success {    
      mail to :vinoddevops501@gmail.com, subject: "the pipeline success"
     }
  }  
}
