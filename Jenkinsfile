pipeline {
    agent { node { label 'workstation' } }



    stages {
        stage('Stage1') {

            steps {

                echo 'Hi there '

                  }
            }
        stage('Stage 2 ') {
            steps {
                echo 'How are you? '
            }
        }
        stage('stage 3 ') {
        environment {
                            SSH_CREDS = credentials('SSH')
                        }
            steps {
                echo 'Hello World'
                sh 'echo "$SSH_CREDS_USR"'
                sh 'echo "$SSH_CREDS_PSW"'
            }
        }
     }
}