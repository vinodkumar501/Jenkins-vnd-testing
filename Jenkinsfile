pipeline {
    agent any 
    stages {
        stage("build") {
          steps {
                retry(30) {
                    sh './flakey-deploy.sh'
                    sh 'echo "tried 30 times but no luck"'
                   }
        }
    }
}
    
}
            
