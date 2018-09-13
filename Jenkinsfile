pipeline {
  agent { label 'slave01' }
  stages {
    stage('Build') {
      steps {
        sh '/etc/profile.d/maven.sh'
        sh 'mvn --version > /home/jenkins/tes'
      }
    }
  }
}
