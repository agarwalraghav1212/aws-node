pipeline {
    agent any

    stages {
        stage('git clone ') {
            steps {
                sh 'cd /desktop/aws-node'
                sh 'pwd'
            }
        }
        stage('build ') {
            steps {
                sh 'npm install'
            }
        }
        stage('deploy ') {
            steps {
                sh 'npm start  app.js'
            }
        }
    }
}
