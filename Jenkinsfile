pipeline {
    agent any

    stages {

        stage('Checkout SCM') {
            steps {
                checkout scm
            }
        }

        stage('Run Script') {
            steps {
                bat 'python firsttrigger.py'
            }
        }

    }
}
