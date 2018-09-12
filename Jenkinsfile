pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World" > /home/eric/tes'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
