pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'GitHub 연동 성공!'
            }
        }
        stage('Python 실행') {
            steps {
                sh 'python hello.py'
            }
        }
    }
}
