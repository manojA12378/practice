pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "SCM Checkout done by Jenkins automatically"
                sh "ls -la"
            }
        }

        stage('Test Pipeline') {
            steps {
                echo "Jenkinsfile is running successfully! 👍"
            }
        }
    }
}
