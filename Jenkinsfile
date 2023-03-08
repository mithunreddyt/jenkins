pipeline {
    agent workstation

    stages {
        stage('Example') {
            steps {
                echo 'Hello Mithun'
            }
        }
    }

    post {
        always {
            echo 'send any email'
        }
    }
}