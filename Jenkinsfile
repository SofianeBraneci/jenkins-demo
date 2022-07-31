pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('build') {
            steps {
                echo 'building'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying to ...'
            }
        }
        stage('testing') {
            steps {
                echo 'test after deploy'
            }
        }
        
        stage('release') {
            steps {
                echo 'releaseing '
            }
        }
    }
}
