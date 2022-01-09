pipeline {
    agent any

    stages {
        stage('Development') {
            steps {
                build 'DevJob'
            }
        }
        stage('Build') {
            steps {
                build 'BuildJob'
            }
        }
        stage('Test') {
            steps {
                build 'TestJob'
            }
        }
    }
}
