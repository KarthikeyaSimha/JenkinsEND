
pipeline {
    agent any

    triggers {
        pollSCM('H/2 * * * *')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building project'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying project'
            }
        }
    }
}
