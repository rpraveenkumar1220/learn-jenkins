pipeline {
    agent { node { label 'workstation' } }
     environment {
       SSH = credentials('SSH')
                }

    stages {
        stage('Stage1') {
            steps {
                echo 'Hi there'
                sh 'echo env'
                 }
            }
        stage('Stage 2 ') {
            steps {
                echo 'How are you?'
            }
        }
        stage('stage 3 ') {

            steps {
                echo 'Hello World'
            }
        }
     }
}