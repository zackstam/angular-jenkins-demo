pipeline {
    agent any

    stages {
        stage('install node modules') {
            steps {
                sh "npm install"
            }
        }
        stage('unit testing') {
            steps {
                sh "npm run test"
            }
        }
        stage('build') {
            steps {
                sh "npm run build"
            }
        }
        stage('Test Integration') {
            steps {
                echo 'Testing'
            }
        }
        stage('Release') {
            steps {
                echo 'Release'
            }
        }
    }
}
