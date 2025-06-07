pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage ('echo') {
            steps {
                sh '''
                    echo "hello"
                '''
            }
        }
    }
}
