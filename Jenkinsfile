pipeline {
    agent any
    tools {
        nodejs 'nodejs-22.14'
    }
    stages{
        stage("Version Test") {
            steps {
                sh "npm install --no-audit"
            }
        }
    }
}