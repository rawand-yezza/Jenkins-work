pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh 'sudo apt-get -y update && sudo apt-get -y upgrade é
      }
    }
    stage('stage 2') {
      steps {
        sh ''' if  if [ 'grep -d git /tmp/paquets' ne 0 ]
        the 
        dpkg -s git 
        else 
        sudo apt-get install -y git 
        fi 
        '''
      }
    }

  }
}
