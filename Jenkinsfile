pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        steps ('echo') {
            sh '''
                echo "hello"
            '''
        }
    }

}
