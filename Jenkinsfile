pipeline {
    agent any
    parameters { 
        string(name: 'NAME', defaultValue: 'World', description: 'Just a name') 
    }
    stages {
        stage('build-docker-image') {
            steps {
                echo "Building docker image..."
            }
        }
        stage('unit-tests'){
            steps {
                echo "Running unit tests in docker container..."
            }
        }
        stage('deploy-prod'){
            steps {
                echo "Deploying to production environment..."
            }
        }
        stage('api-integration-test-prod'){
            steps {
                echo "Running API integration tests for prod..."
            }
        }
        stage('deploy-stg'){
            steps {
                echo "Deploying to stage environment..."
            }
        }
        stage('api-integration-test-stage'){
            steps {
                echo "Running API integration tests for stage..."
            }
        }
        stage('deploy-dev'){
            steps {
                echo "Deploying to dev environment..."
            }
        }
        stage('api-integration-test-dev'){
            steps {
                echo "Running API integration tests for dev..."
            }
        }
    }
}