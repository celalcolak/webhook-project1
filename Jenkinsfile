pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Welcome to Jenkins Environment"
                sh 'echo second step'
                sh 'echo another step'
                sh '''
                echo 'Multiline'
                echo 'Example'
                '''
                sh 'echo using shell inside of Jenkinsfile'
                echo "not using shell outside of Jenkinsfile"
            }
        }
    }
}
