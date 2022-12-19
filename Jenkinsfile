pipeline {
    agent any
    stages {
        stage('Build') {
             steps {
                echo 'Build the repository'
                if (isUnix()) {
                    sh './gradlew clean build'
                } else {
                    bat 'gradlew.bat clean build'
                }
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
