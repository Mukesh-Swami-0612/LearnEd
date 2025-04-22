pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Mukesh-Swami-0612/LearnEd.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the application...'
                // Run build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Run test scripts here
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Docker build/run, move files, restart services etc.
            }
        }
    }
}
