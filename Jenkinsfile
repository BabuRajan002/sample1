pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Pulling...' + env.BRANCH_NAME
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
