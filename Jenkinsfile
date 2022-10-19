pipeline {
    agent {label 'Node A'}
    stages {
        stage('Build') {
            steps {
                // Get some code from a GitHub repository
                git url: 'https://github.com/arnoldrx/aws-codepipeline-github.git', branch: 'main',
                credentialsId: '26f6cf77-07a8-46b7-b275-c25cc3ea44d9'
            }
        }
    }
}