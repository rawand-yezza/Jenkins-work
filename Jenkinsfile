pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'sudo apt-get -y update && sudo apt-get -y upgrade '
      }
    }
    stage('stage 2') {
      steps {
        sh ''' if  if [ 'grep -c git /tmp/paquets' ne 0 ]
        then 
        dpkg -s git 
        else 
        sudo apt-get install -y git 
        fi 
        '''
      }
    }

  }
}
