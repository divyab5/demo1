pipeline {
    agent any
    stages {
        stage('checkout') {
            steps {
                // Get code from a GitHub repository
                git url: 'https://github.com/divyab5/demo1.git', branch: 'main',
                 credentialsId: 'git_cred'
            }
        }
        

    }
}
