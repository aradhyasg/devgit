pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git branch: 'master', url: 'https://github.com/aradhyasg/devgit.git'
            }
        }
        stage('Run Tests') {
            steps {
                sh 'date >> test.txt' // Replace with your specific test command
            }
        }
        stage('Integration Test') {
            steps {
                echo "Hi this is integration"
            }
        }
    }
}
