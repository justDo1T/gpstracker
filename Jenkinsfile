pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build the repository'
                sh './gradlew build'
            }
        }
        stage('Stage 2') {
            steps {
                echo 'Stage 2 here'
            }
        }
        stage('Stage 3') {
            steps {
                echo 'Stage 3 here'
            }
        }
    }
}
