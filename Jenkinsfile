pipeline {
  agent any  
  tools {
    gradle 'gradle'
  }
  stages {
    stage (deploy) {
      steps {
        sh "echo run gradle"
        sh './gradle -v'
      }
    }
  }
}
}
