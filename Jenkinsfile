pipeline {
    agent any

    environment {
        APP_NAME = 'my-application'
        ENVIRONMENT = 'dev'
    }

    stages {
        stage('Build') {
            steps {
                echo "Building ${APP_NAME}"
            }
        }

        stage('Test') {
            steps {
                echo "Testing ${APP_NAME} in ${ENVIRONMENT} environment"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying ${APP_NAME} to ${ENVIRONMENT}"
            }
        }
    }
}