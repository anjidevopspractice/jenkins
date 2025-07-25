pipeline {
    agent {
        node {
            label 'AGENT-1'
        }
    }
    stages {
        stage('build') {
            steps {
                echo 'hello world'
            }
        }
        stage('test') {
            steps {
                echo 'testing'
            }

        }
        stage('deploying') {
            steps {
                echo 'deploying'
            }
        }
    }
}