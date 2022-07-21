pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
            }
        }
        stage('test') {
            steps {
                bat "systeminfo"
            }
        }
        stage('compile') {
            steps {
                echo "testing pr build"
            }
        }
        stage('deploy') {
            steps {
                echo " build"
            }
        }
        stage('compile') {
            steps {
                echo "bye bye!"
            }
        }
    }
}
