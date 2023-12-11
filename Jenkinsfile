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

    stages {
        stage('Stage1') {

            steps {

                echo 'Hi there '
                echo 'env'
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