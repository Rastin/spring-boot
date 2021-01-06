pipeline {
    agent any
    stages {
        stage('checkout git') {
            steps {
                echo 'checkout git ...'
            }
        }

        stage('build') {
            steps {
                echo 'build ...'
            }
        }

        stage ('test') {
            steps {
                echo 'test ..'
            }
        }

        stage('deploy dev'){
            steps {
                echo 'deploy dev...'
            }
        }

        stage('deploy staging'){
            steps {
                echo 'deploy staging ...'
            }
        }

        stage('deploy prod'){
            steps {
                echo 'deploy prod ...'
            }
        }
    }
    post {
        failure {
            echo 'failure ... !'
        }
    }
}
