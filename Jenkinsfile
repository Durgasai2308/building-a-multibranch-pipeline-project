pipeline {
    agent {
        docker {
            image 'ruby'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello world!"'
                sh 'ruby --version'
                sh 'echo "set up webhook"'
                sh 'echo "here is testing webhook"'
            }
        }
    }
}
