pipeline {
    agent { node { label 'workstation' } }
    options { ansiColor('xterm') }
    triggers { pollSCM('H/2 * * * *') }

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