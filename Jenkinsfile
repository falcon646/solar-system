pipeline {
    agent any
    tools {
        nodejs 'nodejs-22.14'
    }
    stages{
        stage("Npm test"){
            steps {
                sh "npm -v"
                sh "node -v"
            }
        }
    }
}