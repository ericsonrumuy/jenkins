pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '/etc/profile.d/maven.sh'
        sh 'mvn --version'
      }
    }
  }
}
