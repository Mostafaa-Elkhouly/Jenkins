@Library('jenkins-shared-library')_
pipeline {
    agent {
        label 'slave1'
    }
    stages {
        stage('nginx from Jenkinsfile') {
            steps {
                // Use the nginx() step from the shared library
                nginx()
            }
        }
    }
}
