pipeline {
    agent {
        docker {
            image 'circleci/node:12.14.0-browsers'
        }
    }
    stages {
        stage('Test') {
            steps {
                sh 'npx crusher-cli test:run --token=adsfsjkdfjksd --project-id=32'
            }
        }
    }
}