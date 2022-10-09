pipeline {
    agent none
    stages {
        stage('pull code') {
            agent {
                label 'slave'
            }
            steps {
                ls
                echo 'pull code successfully'
            }
        }
        stage('build') {
            agent {
                label 'master'
            }
            steps {
                ls
                echo 'build successfully'
            }
        }
        stage('deploy') {
            agent {
                label 'slave'
            }
            steps {
                ls
                echo 'deploy successfully'
            }
        }
    }
}									
