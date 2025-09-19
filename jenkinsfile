pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'Build.bat'
            }
        }

        stage('Test') {
            steps {
                bat 'Test.bat'
            }
        }

        stage('Package') {
            steps {
                bat 'Package.bat'
            }
        }

        stage('Deploy') {
            steps {
                bat 'Deploy.bat'
            }
        }
    }
}
