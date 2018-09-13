pipeline {
  agent { label 'slave01' }
  stages {
    stage('Build') {
      steps {
        sh 'mvn --version > /home/jenkins/tes'
      }
    }
  }
}
