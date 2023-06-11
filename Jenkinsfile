pipeline {
    agent any
    parameters { 
        string(name: 'NAME', defaultValue: 'World', description: 'Just a name') 
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello ${params.NAME}!'
            }
        }
    }
}