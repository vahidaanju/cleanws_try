pipeline {
  agent any 
  stages {
     stage ('cleanWS'){
     steps {
           sh 'sudo rm -r *' 
           sh 'sudo rm -r var/lib/jenkins/workspace/*'
          }
        }
    }
}
