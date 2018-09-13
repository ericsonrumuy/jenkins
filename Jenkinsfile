pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '/etc/profile.d/maven.sh'
        sh '/usr/local/src/apache-maven/bin/mvn --version'
      }
    }
  }
}
