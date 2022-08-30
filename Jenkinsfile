pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                chmod 777 ./jenkins.sh
                ./jenkins.sh
            }
        }
    }
}
