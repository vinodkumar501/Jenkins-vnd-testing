pipeline {
  agent any  
  tools {
    maven 'mvn'
    graddle
  stages {
    stage (deploy) {
      steps {
        sh "echo run app"
        sh "mvn install"
      }
    }
  }
}
}
