pipeline {
    agent any 
    stages {
        stage("build") {
          steps {
                retry(3000) {
                    sh 'echo "Deployment testing"'
                   }
        }
    }
}
    
}
            
