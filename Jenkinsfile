pipeline {
  agent any
  stages {
    stage(build) {
      steps {
        sh echo building an apps"
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
  
    always {
 
       echo 'One way or another, I have finished'
       deleteDir() /* clean up our workspace */
       }
       success {
           echo 'I succeeded!'
       }
       unstable {
           echo 'I unstable!'
       }
       failure {
           echo 'I failed!'
       }
       changed {
           echo 'Things were different before.!'
       }
 }
 
}
