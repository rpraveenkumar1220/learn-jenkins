pipeline {
    agent {
        node { label 'workstation' }
        }

    environment {
                    SSH_CREDENTIAL = credentials('SSH')
                }

    options {
            ansiColor('xterm')
        }

    stages {
        stage('Stage1') {
        parameters {
                string(name: 'Praveen', defaultValue: 'User', description: 'Wish to continue?')
           }
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
            steps {
                echo 'Hello World'
            }
        }
     }
}