pipeline {

    agent any

    stages {
        stage("Code Review") {
            steps {
                sh 'npm install'
                sh "npm run lint"
            }
        }
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
    }
}
