pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Building'
            }
        }
        stage('deploy-ci') {
            steps {
                echo 'Deploying to CI'
            }
        }
        tage('release') {
            steps {
                echo 'Creating versioned release'
            }
        }
        stage('deploy-test') {
            steps {
                echo 'Deploying to TEST'
            }
        }
        stage('deploy-accp') {
            steps {
                echo 'Deploying to ACCP'
            }
        }
    }
}
