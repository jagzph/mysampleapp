pipeline {
    agent any

    stages {
        stage('DEV') {
            steps {
                echo 'Development'
                input 'Enter Name'
            }
        }
        stage('TEST') {
            steps {
                echo 'Test'
            }
        }
        stage('STAGE') {
            steps {
                echo 'Staging'
            }
        }
        stage('PROD') {
            steps {
                echo 'Production'
            }
        }
    }
}
