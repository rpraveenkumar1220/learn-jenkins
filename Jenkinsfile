pipeline {
    agent {
        node { label 'workstation' }
        }
    options {
          ansiColor('xterm')
      }
    environment {
        EXAMPLE_KEY = 'SECRET'
      }

    stages {
        stage('Stage1') {

            steps {

                echo 'Hi there '
                echo environment
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