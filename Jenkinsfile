pipeline {
    agent any
    branches {
        every {
            $class = 'BranchSource'
            spec = '*/test'
        }
    }
    stages {
        stage('Check Files') {
            steps {
                script {
                    // Your build steps here, e.g.,
                    sh 'ls'
                }
            }
        }
        stage('Test') {
            steps {
                script {
                    // Your test steps here, e.g.,
                    sh 'echo "Test"'
                }
            }
        }
        stage('Deploy') {
            steps {
                script {
                    // Your deployment steps here, e.g.,
                    sh 'echo "Deploy"'
                }
            }
        }
    }
}
