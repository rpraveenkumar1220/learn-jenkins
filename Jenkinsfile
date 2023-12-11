pipeline {
    agent {
        node { label 'workstation' }
        }
    options {
          ansiColor('xterm')
      }
    environment {
        EXAMPLE_KEY = credentials('SSH_USR') // Secret value is 'sec%ret'
      }

    stages {
        stage('Stage1') {

            steps {

                echo 'Hi there '
                sh 'env'
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