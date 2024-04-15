pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                echo 'checking-out at main branch'
            }
        }
        stage('test') {
            steps {
                echo 'running the test at main branch'
            }
        }
        stage('build') {
            steps {
                echo 'building the code at main branch'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying from main branch'
                echo 'this is deploying to tomcat'
            }
        }
    }
}
