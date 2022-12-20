pipeline {
    agent any

    tools {
    	jdk 'jdk-17.0.5'
    }

    stages {
        stage('Build') {
             steps {
                echo 'Build the repository'
                sh './gradlew assemble'
            }
        }
        stage('Test') {
            steps {
                echo 'Test the repo'
                sh './gradlew test'
            }
        }
        stage('Stage 3') {
            steps {
                echo 'Stage 3 here'
            }
        }
    }
}
