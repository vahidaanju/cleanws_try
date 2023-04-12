pipeline {
  agent any 
  stages {
    
     stage ('cleanWS'){
     steps {
//            sh'cd..'
//            sh'ls'
           sh 'rm -r /var/lib/jenkins/workspace/ *'
          }
        }
    stage('clone'){
      steps{
        sh'git clone https://github.com/vahidaanju/cleanws_try.git'
      }
    }
   
    }
}
