pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Shreyaaaash/JenkinsDemo.git'
            }
        }

        stage('Restore') {
            steps {
                bat 'dotnet restore'
            }
        }
    }
}
