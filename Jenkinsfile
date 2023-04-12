pipeline {
  agent any 
  stages {
    
     stage ('cleanWS'){
     steps {
           sh'cd..'
           sh'ls'
           sh 'rm -r /var/lib/jenkins/workspace/cleanws_try/cleanws_try@tmp/'
          }
        }
    stage('clone'){
      steps{
        sh'git clone https://github.com/vahidaanju/cleanws_try.git'
      }
    }
   
    }
}
