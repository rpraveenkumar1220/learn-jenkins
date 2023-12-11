pipeline {
    agent {
        node { label 'workstation' }
        }
    options {
        ansiColor('xterm')
            }
    environment {
        SSH_CREDENTIALS = credentials('SSH')
                }
    parameters {
        string(name: 'Praveen', defaultValue: '', description: 'Do you wish to continue?')
            }


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
            steps {
                echo 'Hello World'
            }
        }
     }
}