pipeline {
    agent any // Specifies the agent where the pipeline should run (e.g., any available agent)

    stages {
        stage('Build') {
            steps {
                // Define build steps here
                sh 'echo "Building the project"'
            }
        }

        stage('Test') {
            steps {
                // Define test steps here
                sh 'echo "Running tests"'
            }
        }

        stage('Deploy') {
            steps {
                // Define deployment steps here
                sh 'echo "Deploying the application"'
            }
        }
    }

    post {
        success {
            // Actions to take if the pipeline succeeds
            sh 'echo "Pipeline succeeded"'
        }
        failure {
            // Actions to take if the pipeline fails
            sh 'echo "Pipeline failed"'
        }
    }
}
