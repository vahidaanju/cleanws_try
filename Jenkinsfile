pipeline {
  agent any 
  stages {
    stage ('unset proxy') {
      steps {
        sh 'git config --global --unset http.proxy'
        sh 'git config --global user.name "vahidaanju"'
        sh 'git config --global user.email "vahida.anju@ciyes.com"'
      }
    }
    stage('clone'){
      steps{
        sh 'git clone https://github.com/vahidaanju/cleanws_try.git'
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
