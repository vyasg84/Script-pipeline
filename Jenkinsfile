pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                chmod u+x ./pipeline.sh
                ./pipeline.sh
            }
        }
    }
}
