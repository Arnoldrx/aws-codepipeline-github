pipeline {
    agent {label 'Node A'}
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git url: 'https://github.com/Arnoldrx/aws-codepipeline-github.git', branch: 'main',
                credentialsId: 'github_token'
            }
        }
    }
}