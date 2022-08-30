pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                chmod u+x ./jenkins.sh
                ./jenkins.sh
            }
        }
    }
}
