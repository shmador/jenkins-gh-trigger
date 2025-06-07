pipeline {
    agent any
    triggers {
        pollSCM('H/1 * * * *')
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
