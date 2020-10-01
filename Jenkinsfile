pipeline {
    agent any
    stages {
        stage('ok') {
            steps {
                echo "ok"
            }
        }
    }
    post {
        always {
            emailext body: '''ssssssssssss
dddddddddddddddddd''', subject: 'From Jenkins', to: 'thinklikesruthi@gmail.com'
        }
    }
}
