pipeline {
    agent any

    stages {
        stage('git clone https://github.com/agarwalraghav1212/aws-node.git') {
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
                sh 'pm2 start  app.js'
            }
        }
    }
}
