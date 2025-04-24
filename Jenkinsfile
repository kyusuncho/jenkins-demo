pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                git '[사용자 레포지토리 URL]'
                sh "mvn clean package"
            }

        }
    }
}