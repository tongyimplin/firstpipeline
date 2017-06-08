pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '''
                    java -version
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
