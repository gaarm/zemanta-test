#!groovy

node {
    try {
        stage('Code checkout') {
            dir('b1') {
                checkout scm
                sh 'sudo git clean --force -d -x'
            }
        }

        stage('Docker build') {
        }

        stage('Build AutoML Artifacts') {
        }

        stage("Push AutoML Artifacts") {
        }
    } finally {
    }
}
