pipeline {
    agent any

    options {
        
        customWorkspace '/mnt/CICDDevopsPoeject'
    }

    stages {
        stage('Build') {
            steps {
                // Your build steps here
                sh 'echo "Building..."'
            }
        }
        stage('Test') {
            steps {
                // Your test steps here
                sh 'echo "Testing..."'
            }
        }
        stage('Deploy') {
            steps {
                // Your deployment steps here
                sh 'echo "Deploying..."'
            }
        }
    }

    post {
        always {
            // Clean up workspace after pipeline execution
            cleanWs()
        }
    }
}
