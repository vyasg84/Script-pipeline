pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                git branch: 'main', credentialsId: '3be43866-0bec-4c57-b6c4-95c91d798499', url: 'https://github.com/vyasg84/Script-pipeline.git'
                sh "chmod +x -R ./pipeline.sh"
                sh "./pipeline.sh"
                
            }
        }
    }
}
