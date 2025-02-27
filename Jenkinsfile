pipeline {
    agent any
    tools {
        nodejs 'nodejs-22.14'
    }
    stages{
        stage("Install Dependencies") {
            steps {
                sh "npm install --no-audit"
            }
        }
        stage("Npm Dependency Audit"){
            sh 'npm audit --audit-level=critical'
        }
    }
}