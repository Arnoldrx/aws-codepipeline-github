pipeline {
    agent any
    tools {
        maven "Local_Maven"
    }
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git url: 'https://github.com/arnoldrx/aws-codepipeline-github.git', branch: 'main'
            }
        }
    }
}