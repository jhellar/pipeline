pipeline {
    agent none
    stages {
        stage('Run Tests') {
            parallel {
                stage('Test On Windows') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
                stage('Test On Linux') {
                    steps {
                        echo 'Hello world!' 
                    }
                }
            }
        }
    }
}
