pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                java -version
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
