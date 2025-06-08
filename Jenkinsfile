pipeline {
    agent any
    triggers {
        pollSCM('* * * * *')
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
