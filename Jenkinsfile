pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'python3.5 $WORKSPACE/hello.py'
            }
        }
    }
}
