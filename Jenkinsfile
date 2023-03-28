pipeline {
  agent any
  stages {
    stage('update') {
      steps {
        sh '''apt update -y
apt install nginx -y'''
      }
    }

  }
}