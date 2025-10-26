pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Run Script') {
            steps {
                sh 'python3 hello.py'
            }
        }
    }
}
