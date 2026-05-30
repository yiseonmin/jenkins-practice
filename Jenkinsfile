pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
                echo 'GitHub 연동 성공!'
                echo "Branch: ${env.BRANCH_NAME}"
            }
        }
    }
}
