pipeline {
    agent none
    stages {
        stage('pull code') {
            agent {
                label 'master'
            }
            steps {
                echo 'pull code successfully'
                echo '$Subject'
            }
        }
        stage('build') {
            agent {
                label 'master'
            }
            steps {
                echo 'build successfully'
            }
        }
        stage('deploy') {
            agent {
                label 'master'
            }
            steps {
                echo 'deploy successfully'
            }
        }
    }
}									
