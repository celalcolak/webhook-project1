pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Welcome to Jenkins Environment"
                sh 'echo second step'
                sh 'echo another step'
                sh '''
                echo 'Multiline'
                echo 'Example'
                '''
                echo "not using shell"
            }
        }
    }
}