pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'GitHub 연동 성공!'
            }
        }
        stage('Python 설치') {
            steps {
                sh 'apt-get install -y python3'
            }
        }
        stage('Python 실행') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
