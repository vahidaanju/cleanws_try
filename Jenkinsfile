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
           sh'cd..'
           sh'ls'
           sh 'rm -r /var/lib/jenkins/workspace/devopstest'
          }
        }
    }
}
