pipeline {
    agent any

    stages {

        stage('Stage 1') {
            steps {
                sh 'sleep 5'
                echo "check"
            }
        }

        stage('Stage 2') {
            steps {
                sh '''
                    #!/bin/bash
                    pwd
                    ls -lrt
                    sleep 5
                '''
                echo "check"
            }
        }

    }
}
