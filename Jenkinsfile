pipeline {
    agent any

    stages {

        stage('System Info') {
            steps {
                sh 'echo "Current User:"'
                sh 'whoami'

                sh 'echo "Current Directory:"'
                sh 'pwd'

                sh 'echo "Hostname:"'
                sh 'hostname'
            }
        }

        stage('Files') {
            steps {
                sh 'echo "Listing Files:"'
                sh 'ls -la'
            }
        }
    }
}
