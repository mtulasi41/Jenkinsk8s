pipeline {

  agent any

  stages {

    stage('Checkout Source') {
      steps {
        checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-credential', url: 'https://github.com/mtulasi41/Jenkinsk8s.git']])
      }
    } 
    
  }
}
