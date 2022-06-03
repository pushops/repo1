pipeline {
    agent any

    stages {
        stage('Chekout') {
            steps {
                git url:git branch: 'main', url: 'https://github.com/pushops/repo1.git'
                echo 'Checkout Completed'
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
