pipeline {
  agent any 
  stages {
    
    stage('clone'){
      steps{
        sh'git clone https://github.com/vahidaanju/cleanws_try.git'
      }
    }
   
     stage ('cleanWS'){
     steps {
           sh 'cd /var/lib/jenkins/workspace' 
           sh 'rm -r *'
          }
        }
    }
}
