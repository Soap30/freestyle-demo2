pipeline {

    agent any

    stages {

        stage('run.sh') {   
            steps {
                sh '''
                sh run.sh
                '''
            }

        }

        stage('Hello') {
            steps {
                sh '''
                echo "Hi Class, this is a pipeline"
                '''
            }
        }
    }
}