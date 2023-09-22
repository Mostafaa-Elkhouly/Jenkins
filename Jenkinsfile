@Library('jenkins-shared-library')_
pipeline {
    agent {
        label 'slave1'
    }
    stages {
        stage('Build') {
            steps {
                // Use the nginx() step from the shared library
                nginx() {
                    sh 'sudo echo "welcome from Jenkinsfile in GitHub" >> /var/www/html/index.html'
                }
            }
        }
    }
}

nginx()
