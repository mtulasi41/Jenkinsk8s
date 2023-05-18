pipeline {

  agent any

  stages {

    stage('Checkout Source') {
      steps {
        checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/mtulasi41/Jenkinsk8s.git']])'
      }
    } 
    
  }
}
