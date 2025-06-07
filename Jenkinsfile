pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage ('echo') {
            sh '''
                echo "hello"
            '''
        }
    }

}
